{
  "info": {
    "name": "Github Get Users Username Following Targetuser",
    "_postman_id": "fd862ef7-d3f2-4989-a902-9741faebabda",
    "description": "Check if one user follows another.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "65bbf7a3-3151-4b5a-b9ef-b1ca9c612cc2",
          "name": "check-if-one-user-follows-another",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/following/:targetUser"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "targetUser",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "Is used to set specified media type",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Check if one user follows another"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b988ec0-21a3-4d14-bec0-ea387c3cb10d"
            }
          ]
        }
      ]
    }
  ]
}
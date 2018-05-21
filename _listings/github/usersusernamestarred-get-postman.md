{
  "info": {
    "name": "Github Get Users Username Starred",
    "_postman_id": "52094c71-ca6b-4b10-a2b0-1396a61933b5",
    "description": "List repositories being starred by a user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "5c9c8806-b59b-4afe-95b5-a97c989aabd2",
          "name": "list-repositories-being-starred-by-a-user",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/starred"
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
            "description": "List repositories being starred by a user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "557b650b-1093-4794-94b3-27aacb0ca9e2"
            }
          ]
        }
      ]
    }
  ]
}
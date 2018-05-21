{
  "info": {
    "name": "Github Get Users Username Followers",
    "_postman_id": "82f56b06-6c31-4a70-a0c7-35ea6aeac079",
    "description": "List a user's followers",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "2d55fc55-15db-4cee-bd25-7d94c00b9450",
          "name": "list-a-users-followers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/followers"
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
            "description": "List a user's followers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a98a17f-9366-4591-8479-e214e4346689"
            }
          ]
        }
      ]
    }
  ]
}
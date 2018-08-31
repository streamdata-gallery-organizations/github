{
  "info": {
    "name": "Github Get Users Username Subscriptions",
    "_postman_id": "cfa79b4d-8a79-43fb-96a0-548b4efaa468",
    "description": "List repositories being watched by a user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "9f20bc70-7594-423b-ad8b-4adcfe86c9f6",
          "name": "list-repositories-being-watched-by-a-user",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/subscriptions"
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
            "description": "List repositories being watched by a user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9eff64e2-e136-494d-b8aa-731f9c66c771"
            }
          ]
        }
      ]
    }
  ]
}
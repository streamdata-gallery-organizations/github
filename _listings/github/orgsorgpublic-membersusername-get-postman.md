{
  "info": {
    "name": "Github Get Orgs Org Public Members Username",
    "_postman_id": "4327d0c3-d76c-41d8-9e51-ec900ed7ab49",
    "description": "Check public membership.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "orgs",
      "item": [
        {
          "id": "2dec711a-23c1-451c-8d02-5a04256a5c93",
          "name": "check-public-membership",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "orgs/:org/public_members/:username"
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
                  "id": "org",
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
            "description": "Check public membership"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "455c204a-bf0d-4779-943c-b6c2ce8bdb32"
            }
          ]
        }
      ]
    }
  ]
}
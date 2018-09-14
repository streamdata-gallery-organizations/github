{
  "info": {
    "name": "Github Get Users Username",
    "_postman_id": "2fc29001-c3ad-40c8-b965-a65ccc50f40c",
    "description": "Get a single user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "ad6282ea-c166-4fcb-b79a-0c42297d2535",
          "name": "get-a-single-user",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username"
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
            "description": "Get a single user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea72c7f6-4549-49c6-b87a-686ba48c1e35"
            }
          ]
        }
      ]
    }
  ]
}
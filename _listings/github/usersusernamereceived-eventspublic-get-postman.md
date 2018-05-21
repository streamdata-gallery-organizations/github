{
  "info": {
    "name": "Github Get Users Username Received Events Public",
    "_postman_id": "58f5f9f2-d16f-46b6-9e6c-ab3094eb3102",
    "description": "List public events that a user has received",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "10117d3e-8a02-4e01-af7c-5d00683be9df",
          "name": "list-public-events-that-a-user-has-received",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/received_events/public"
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
            "description": "List public events that a user has received"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe1f14c0-0a1a-4755-a61e-e073a7c00ad8"
            }
          ]
        }
      ]
    }
  ]
}
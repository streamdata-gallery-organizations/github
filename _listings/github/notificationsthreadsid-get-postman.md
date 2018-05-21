{
  "info": {
    "name": "Github Get Notifications Threads",
    "_postman_id": "a44b1b17-5740-4c3d-af67-131f1b6d8538",
    "description": "View a single thread.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "notifications",
      "item": [
        {
          "id": "8668e6fc-9cc1-49a4-b4a7-2815379de8bb",
          "name": "view-a-single-thread",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "notifications/threads/:id"
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
                  "id": "id",
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
            "description": "View a single thread"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94d634cc-0327-47db-896f-773786c5fcaf"
            }
          ]
        }
      ]
    }
  ]
}
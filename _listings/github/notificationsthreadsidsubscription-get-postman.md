{
  "info": {
    "name": "Github Get Notifications Threads  Subscription",
    "_postman_id": "17c80503-05b1-497f-9ff9-051a5c4a3da8",
    "description": "Get a Thread Subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "notifications",
      "item": [
        {
          "id": "f68b3a37-4061-4d8d-b9ee-3963d5ef4acc",
          "name": "get-a-thread-subscription",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "notifications/threads/:id/subscription"
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
            "description": "Get a Thread Subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5deed966-ab1f-44e6-b3a5-839db6853e73"
            }
          ]
        }
      ]
    }
  ]
}
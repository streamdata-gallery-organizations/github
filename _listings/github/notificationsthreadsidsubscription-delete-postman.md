{
  "info": {
    "name": "Github Delete Notifications Threads  Subscription",
    "_postman_id": "b3792138-d4f0-4455-a352-6fb0a82d8e67",
    "description": "Delete a Thread Subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "notifications",
      "item": [
        {
          "id": "d8826229-9d72-4641-85b8-6c88dcfa6b47",
          "name": "delete-a-thread-subscription",
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
            "method": "DELETE",
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
            "description": "Delete a Thread Subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "64a11c8b-b612-4b8e-8656-4be3af2c5c80"
            }
          ]
        }
      ]
    }
  ]
}
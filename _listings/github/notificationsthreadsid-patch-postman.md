{
  "info": {
    "name": "Github Patch Notifications Threads",
    "_postman_id": "e79f6c29-5e20-4167-9a9c-ac6de25088f2",
    "description": "Mark a thread as read",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "notifications",
      "item": [
        {
          "id": "4a55f33f-600d-480e-94b5-165c6b47770c",
          "name": "mark-a-thread-as-read",
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
            "method": "PATCH",
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
            "description": "Mark a thread as read"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b7e0680d-dc13-4225-8fdd-8972e3050ca5"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Github Get Gists  Comments Comment",
    "_postman_id": "0726809b-465b-41c9-bd68-236b2c9b98fb",
    "description": "Get a single comment.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "gists",
      "item": [
        {
          "id": "f2821a4d-9a1c-4744-9eee-9189e8eadada",
          "name": "get-a-single-comment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "gists/:id/comments/:commentId"
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
                  "id": "commentId",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Get a single comment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eba67825-4a87-4355-b313-c98db24eb5be"
            }
          ]
        }
      ]
    }
  ]
}
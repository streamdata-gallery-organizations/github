{
  "info": {
    "name": "Github Get Gitignore Templates Language",
    "_postman_id": "6e3c8419-ab82-4837-b671-0448c5caf34f",
    "description": "Get a single template.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "gitignore",
      "item": [
        {
          "id": "26c1b98d-fa7c-4d32-9c63-daac5faacaec",
          "name": "get-a-single-template",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "gitignore/templates/:language"
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
                  "id": "language",
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
            "description": "Get a single template"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78bae551-5e4d-45b6-a40a-2b30a4669a3f"
            }
          ]
        }
      ]
    }
  ]
}
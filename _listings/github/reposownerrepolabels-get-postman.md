{
  "info": {
    "name": "Github Get Repos Owner Repo Labels",
    "_postman_id": "5ed0b0d1-83df-4d05-aba9-0b45f0b0cec3",
    "description": "List all labels for this repository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "db8e306c-1c9a-4ba5-9b21-e1880acd91e2",
          "name": "list-all-labels-for-this-repository",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/labels"
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
                  "id": "owner",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "repo",
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
            "description": "List all labels for this repository"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e39273ac-8d46-42a5-a1c1-21c240b6fe6a"
            }
          ]
        }
      ]
    }
  ]
}
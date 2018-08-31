{
  "info": {
    "name": "Github Get Repos Owner Repo Subscription",
    "_postman_id": "7f42719d-7a24-4017-b835-4aca8f0d5fcc",
    "description": "Get a Repository Subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "0f36eee4-7dec-47ea-91b4-096491f53458",
          "name": "get-a-repository-subscription",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/subscription"
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
            "description": "Get a Repository Subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd4c8c81-5b6d-48c0-a638-0bfa28cb6dd3"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Github Get Repos Owner Repo Pulls",
    "_postman_id": "8e4a78b2-c95c-441b-a285-909b8413bdb6",
    "description": "List pull requests.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "45f9414f-e8af-47d7-adda-8bdc943a8aba",
          "name": "list-pull-requests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/pulls"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "base",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "head",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "state",
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
            "description": "List pull requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "091cd8db-05dc-4450-98e1-af2d7e93f6d8"
            }
          ]
        }
      ]
    }
  ]
}
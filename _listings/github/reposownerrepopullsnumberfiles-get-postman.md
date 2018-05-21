{
  "info": {
    "name": "Github Get Repos Owner Repo Pulls Number Files",
    "_postman_id": "be622c10-1eb6-42e5-8ea7-1a35fbcc9cab",
    "description": "List pull requests files.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "7f071d90-6293-40d6-a6c4-a8f2d42ca837",
          "name": "list-pull-requests-files",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/pulls/:number/files"
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
                  "id": "number",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "List pull requests files"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4852386c-f58a-42f9-86e0-9df96910d230"
            }
          ]
        }
      ]
    }
  ]
}
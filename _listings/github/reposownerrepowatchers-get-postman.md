{
  "info": {
    "name": "Github Get Repos Owner Repo Watchers",
    "_postman_id": "3cc7525f-6dc4-4166-9704-579c1ae9b3b6",
    "description": "List Stargazers. New implementation.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "7448734c-a9cf-40af-90ae-046b269fecf8",
          "name": "list-stargazers-new-implementation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/watchers"
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
            "description": "List Stargazers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71d53ab0-cc37-40e4-80a3-f35cec9b865c"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Github Get Repos Owner Repo Pulls Number Merge",
    "_postman_id": "8812c955-4eb4-4bfa-989b-2110570a181d",
    "description": "Get if a pull request has been merged.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "0cc151b1-aac6-4d92-a411-67a2d3a4d7a7",
          "name": "get-if-a-pull-request-has-been-merged",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/pulls/:number/merge"
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
            "description": "Get if a pull request has been merged"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5bad3cb8-0fb7-494f-8339-f57f8152745f"
            }
          ]
        }
      ]
    }
  ]
}
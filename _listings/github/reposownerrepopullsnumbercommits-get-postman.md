{
  "info": {
    "name": "Github Get Repos Owner Repo Pulls Number Commits",
    "_postman_id": "2426876b-0e4d-47d1-b84a-5ee37569c089",
    "description": "List commits on a pull request.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "7b988d52-1b6a-4c75-953d-0613f6e22455",
          "name": "list-commits-on-a-pull-request",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/pulls/:number/commits"
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
            "description": "List commits on a pull request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d37d9cd5-1df1-4fdb-aee2-e0888145bfa7"
            }
          ]
        }
      ]
    }
  ]
}
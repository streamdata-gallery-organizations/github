{
  "info": {
    "name": "Github Get Repos Owner Repo Pulls Number Comments",
    "_postman_id": "759f652e-35c9-4bd3-b0c2-76d160765ae8",
    "description": "List comments on a pull request.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "b51900d7-a6de-4800-9c8e-8330edcaeb30",
          "name": "list-comments-on-a-pull-request",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/pulls/:number/comments"
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
            "description": "List comments on a pull request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30683c71-8a6d-4781-a90a-f1132cc7c170"
            }
          ]
        }
      ]
    }
  ]
}
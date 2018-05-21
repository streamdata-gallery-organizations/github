{
  "info": {
    "name": "Github Get Repos Owner Repo Tags",
    "_postman_id": "73bfd2e4-94b2-44f7-a4cd-f3c11f075e2c",
    "description": "Get list of tags.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "68149c2a-70fd-4419-b746-3429df66913a",
          "name": "get-list-of-tags",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/tags"
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
            "description": "Get list of tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17937cbe-d556-4f66-bb63-c52d5ef8c2a9"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "GitHub",
    "_postman_id": "62d8d098-b805-43d1-b27d-d8e63a7cffdb",
    "description": "GitHub is the best place to share code with friends, co-workers, classmates, and complete strangers. Over 24 million people use GitHub to build amazing things together across 67 million repositories. With the collaborative features of GitHub.com and GitHub Business, it has never been easier for individuals and teams to write faster, better code.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "d538ef46-f772-4ecc-9210-377271cf352d",
          "name": "get-a-single-release-asset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/releases/assets/:id"
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
                  "id": "id",
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
            "description": "Get a single release asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1acd6bc4-2e0f-44b8-916f-083619048c41"
            }
          ]
        }
      ]
    }
  ]
}
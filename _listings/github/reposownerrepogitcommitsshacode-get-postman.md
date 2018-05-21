{
  "info": {
    "name": "Github Get Repos Owner Repo Git Commits Shacode",
    "_postman_id": "3a60808e-7db7-4f3f-b1f9-a0e0af358068",
    "description": "Get a Commit.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "fc6ba77b-1f5d-4b33-a309-818c4d4618df",
          "name": "get-a-commit",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/git/commits/:shaCode"
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
                },
                {
                  "id": "shaCode",
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
            "description": "Get a Commit"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4810d2c8-287c-456c-ba6f-78c708137e98"
            }
          ]
        }
      ]
    }
  ]
}
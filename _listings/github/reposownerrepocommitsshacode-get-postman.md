{
  "info": {
    "name": "Github Get Repos Owner Repo Commits Shacode",
    "_postman_id": "aa246f99-c19f-4ed2-8f58-e4b114ffc0a2",
    "description": "Get a single commit.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "55b44fdc-90a1-4c70-a0ff-2b6a7597943d",
          "name": "get-a-single-commit",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/commits/:shaCode"
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
            "description": "Get a single commit"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04637747-15d0-4aaa-b018-2205ba172961"
            }
          ]
        }
      ]
    }
  ]
}
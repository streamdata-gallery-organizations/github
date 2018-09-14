{
  "info": {
    "name": "Github Get Legacy Issues Search Owner Repository State Keyword",
    "_postman_id": "02dcf18e-9770-4f11-af59-bac8b8d99d35",
    "description": "Find issues by state and keyword.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "legacy",
      "item": [
        {
          "id": "3213a7d4-dfeb-40a5-ad78-3c6ff726185c",
          "name": "find-issues-by-state-and-keyword",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "legacy/issues/search/:owner/:repository/:state/:keyword"
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
                  "id": "keyword",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "owner",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "repository",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "state",
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
            "description": "Find issues by state and keyword"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ddb0f19-cb9b-4733-992d-62bea3ce7e00"
            }
          ]
        }
      ]
    }
  ]
}
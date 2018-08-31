{
  "info": {
    "name": "Github Get Repos Owner Repo Statuses Ref",
    "_postman_id": "6376cd97-475e-4ba0-b031-de1b5dcd2ce8",
    "description": "List Statuses for a specific Ref.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "eee5b9de-5a30-4d93-b927-390cc3669ac9",
          "name": "list-statuses-for-a-specific-ref",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/statuses/:ref"
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
                  "id": "ref",
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
            "description": "List Statuses for a specific Ref"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23865af4-2937-4eda-b193-8072ab19c9ab"
            }
          ]
        }
      ]
    }
  ]
}
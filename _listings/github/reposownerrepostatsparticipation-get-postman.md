{
  "info": {
    "name": "Github Get Repos Owner Repo Stats Participation",
    "_postman_id": "0068f96f-99e1-4c97-a3cc-259c75d0b7fa",
    "description": "Get the weekly commit count for the repo owner and everyone else.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "e99dd83c-c245-46fd-80ef-c7191552140b",
          "name": "get-the-weekly-commit-count-for-the-repo-owner-and-everyone-else",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/stats/participation"
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
            "description": "Get the weekly commit count for the repo owner and everyone else"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9ef5db9-ff06-4663-9b0f-d558442bb335"
            }
          ]
        }
      ]
    }
  ]
}
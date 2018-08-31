{
  "info": {
    "name": "Github Delete Repos Owner Repo Issues Number Labels",
    "_postman_id": "2adbeeeb-80a3-47ad-a1c9-4adfe7a95078",
    "description": "Remove all labels from an issue.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "0fae198c-c3ee-4773-89af-f985e9c5e945",
          "name": "remove-all-labels-from-an-issue",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/issues/:number/labels"
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
            "method": "DELETE",
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
            "description": "Remove all labels from an issue"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76f0b6e0-d378-4025-9c56-08af384cbed3"
            }
          ]
        }
      ]
    }
  ]
}
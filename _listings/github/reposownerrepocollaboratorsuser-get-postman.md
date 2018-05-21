{
  "info": {
    "name": "Github Get Repos Owner Repo Collaborators User",
    "_postman_id": "2442d0b3-2e67-4a56-ae10-60427e6c34c0",
    "description": "Check if user is a collaborator",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "0aa15d85-71df-4411-a3f0-ab0ca2266c0a",
          "name": "check-if-user-is-a-collaborator",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/collaborators/:user"
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
                  "id": "user",
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
            "description": "Check if user is a collaborator"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d9ff41b-6179-460e-b357-4399fdd419fc"
            }
          ]
        }
      ]
    }
  ]
}
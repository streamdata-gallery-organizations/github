{
  "info": {
    "name": "Github Put Repos Owner Repo Collaborators User",
    "_postman_id": "07621cf9-ee04-46c8-8b85-47d3b8643349",
    "description": "Add collaborator.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "0c2dacd3-41b7-4c17-935b-dd885cfae2e1",
          "name": "add-collaborator",
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
            "method": "PUT",
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
            "description": "Add collaborator"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47594d6a-215e-423b-9ed2-6f2b12b6b2c4"
            }
          ]
        }
      ]
    }
  ]
}
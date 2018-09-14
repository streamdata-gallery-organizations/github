{
  "info": {
    "name": "Github Delete Repos Owner Repo Subscription",
    "_postman_id": "b3e105d4-8765-46b1-819d-f7a30d02b64d",
    "description": "Delete a Repository Subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "bdfcb8fd-8f7e-4226-a54c-20d75713898b",
          "name": "delete-a-repository-subscription",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/subscription"
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
            "description": "Delete a Repository Subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "647e1a1a-0b84-4c9b-b46f-f8e0bf0bbeb2"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Github Delete Repos Owner Repo Downloads Download",
    "_postman_id": "738f30ad-8455-4450-8253-1e24afc32011",
    "description": "Deprecated. Delete a download.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "227436d5-3c53-4717-bbcd-b9afe04924e5",
          "name": "deprecated-delete-a-download",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/downloads/:downloadId"
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
                  "id": "downloadId",
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
            "description": "Deprecated"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d178cee-af91-4da3-bcd6-3d136a9f7978"
            }
          ]
        }
      ]
    }
  ]
}
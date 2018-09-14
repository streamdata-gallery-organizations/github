{
  "info": {
    "name": "GitHub",
    "_postman_id": "55cad2ba-869f-42f7-b30b-399df711ecae",
    "description": "GitHub is the best place to share code with friends, co-workers, classmates, and complete strangers. Over 24 million people use GitHub to build amazing things together across 67 million repositories. With the collaborative features of GitHub.com and GitHub Business, it has never been easier for individuals and teams to write faster, better code.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "85c34711-e57b-432f-9461-05a03f751c76",
          "name": "delete-a-release-asset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/releases/assets/:id"
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
                  "id": "id",
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
            "description": "Delete a release asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1bf8f14-840a-4d15-b480-02a49a02b775"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "GitHub",
    "_postman_id": "a9988b77-8047-4c25-9d85-a2643e8f114e",
    "description": "GitHub is the best place to share code with friends, co-workers, classmates, and complete strangers. Over 24 million people use GitHub to build amazing things together across 67 million repositories. With the collaborative features of GitHub.com and GitHub Business, it has never been easier for individuals and teams to write faster, better code.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "ba254819-1f41-483b-b1b8-0b9030e7e37a",
          "name": "list-assets-for-a-release",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/releases/:id/assets"
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
            "description": "List assets for a release"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33eff27e-5605-4ade-ba14-f2ae2cea3541"
            }
          ]
        }
      ]
    }
  ]
}
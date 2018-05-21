{
  "info": {
    "name": "Github Get Repos Owner Repo Downloads",
    "_postman_id": "1e964d95-ebd9-4286-a8dc-bb1f0543788f",
    "description": "Deprecated. List downloads for a repository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "fce40536-1ff0-418a-bb95-6e600ffaf169",
          "name": "deprecated-list-downloads-for-a-repository",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/downloads"
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
            "description": "Deprecated"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b36a4800-8480-4bca-9888-b55428e4509c"
            }
          ]
        }
      ]
    }
  ]
}
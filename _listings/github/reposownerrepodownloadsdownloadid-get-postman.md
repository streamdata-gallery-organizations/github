{
  "info": {
    "name": "Github Get Repos Owner Repo Downloads Download",
    "_postman_id": "c97d37cf-635d-4eeb-9d7f-fceab35eb3fb",
    "description": "Deprecated. Get a single download.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "2376ac92-bd90-4a38-8dca-a8ffcbb7e5c7",
          "name": "deprecated-get-a-single-download",
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
              "id": "c884d449-196a-40c7-b897-3c28062db1ee"
            }
          ]
        }
      ]
    }
  ]
}
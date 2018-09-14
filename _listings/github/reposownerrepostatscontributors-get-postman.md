{
  "info": {
    "name": "Github Get Repos Owner Repo Stats Contributors",
    "_postman_id": "ce2f65ce-e230-411a-a55f-575571108484",
    "description": "Get contributors list with additions, deletions, and commit counts.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "9ea18e6e-658c-4973-a2ae-bae9b1828451",
          "name": "get-contributors-list-with-additions-deletions-and-commit-counts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/stats/contributors"
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
            "description": "Get contributors list with additions, deletions, and commit counts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d825f2e-12de-4617-8648-910bc952f262"
            }
          ]
        }
      ]
    }
  ]
}
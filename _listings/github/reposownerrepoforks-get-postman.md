{
  "info": {
    "name": "Github Get Repos Owner Repo Forks",
    "_postman_id": "4aa8f55c-8028-4d59-a46b-8298e58dbe89",
    "description": "List forks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "0fe43ebe-1a6a-456c-96bf-34ae17d95f38",
          "name": "list-forks",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/forks"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort",
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
            "description": "List forks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "676ceea5-a92d-491e-8f1b-eb8b4a7b33c5"
            }
          ]
        }
      ]
    }
  ]
}
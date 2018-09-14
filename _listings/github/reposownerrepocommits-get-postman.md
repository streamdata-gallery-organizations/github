{
  "info": {
    "name": "Github Get Repos Owner Repo Commits",
    "_postman_id": "cea0b44b-81b7-4e1c-a659-4faf29b76cae",
    "description": "List commits on a repository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "3d22a6ec-e4c5-44e4-a92e-911b1b8e9194",
          "name": "list-commits-on-a-repository",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/commits"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "author",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "path",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sha",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "since",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "until",
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
            "description": "List commits on a repository"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fb1bca0-c68c-4db1-bfe1-5cae8e330278"
            }
          ]
        }
      ]
    }
  ]
}
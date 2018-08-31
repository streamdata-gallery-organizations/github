{
  "info": {
    "name": "Github Get Repos Owner Repo Pulls Comments",
    "_postman_id": "ec19af01-6e77-4511-a1fb-f9adfea2bb9a",
    "description": "List comments in a repository.\nBy default, Review Comments are ordered by ascending ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "35e7de4b-5576-4fe4-b36a-de5ba8bb18e0",
          "name": "list-comments-in-a-repositoryby-default-review-comments-are-ordered-by-ascending-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/pulls/comments"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "direction",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "since",
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
            "description": "List comments in a repository"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4962b311-893c-4d0d-b586-39a0432b658a"
            }
          ]
        }
      ]
    }
  ]
}
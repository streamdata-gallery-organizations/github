{
  "info": {
    "name": "Github Get Repos Owner Repo Comments",
    "_postman_id": "78a1eb46-c4fa-40e1-b005-7e303a97852d",
    "description": "List commit comments for a repository.\nComments are ordered by ascending ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "d1527c36-5cde-4186-8d9e-741d7ef91ae2",
          "name": "list-commit-comments-for-a-repositorycomments-are-ordered-by-ascending-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/comments"
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
            "description": "List commit comments for a repository"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f67f1d6-5c4f-4117-9297-4e122dba0b76"
            }
          ]
        }
      ]
    }
  ]
}
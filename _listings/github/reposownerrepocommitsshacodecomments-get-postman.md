{
  "info": {
    "name": "Github Get Repos Owner Repo Commits Shacode Comments",
    "_postman_id": "946106e6-5b07-4665-8f38-64ffa638e302",
    "description": "List comments for a single commitList comments for a single commit.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "f4a96f4b-b8bd-404f-99f3-94b5e6f74d28",
          "name": "list-comments-for-a-single-commitlist-comments-for-a-single-commit",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/commits/:shaCode/comments"
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
                },
                {
                  "id": "shaCode",
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
            "description": "List comments for a single commitList comments for a single commit"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "343c7d21-6486-4fa1-b205-b1a13ac5bfbc"
            }
          ]
        }
      ]
    }
  ]
}
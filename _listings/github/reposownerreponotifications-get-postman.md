{
  "info": {
    "name": "Github Get Repos Owner Repo Notifications",
    "_postman_id": "2d1e4d62-c0dd-4494-b54c-e1060109fabc",
    "description": "List your notifications in a repository\nList all notifications for the current user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "af2644b1-375c-4f54-8ffb-29a299cdf6c8",
          "name": "list-your-notifications-in-a-repositorylist-all-notifications-for-the-current-user",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/notifications"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "participating",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "since",
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
            "description": "List your notifications in a repository\nList all notifications for the current user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "748908d5-fc25-4e80-aa22-57914bf7f52d"
            }
          ]
        }
      ]
    }
  ]
}
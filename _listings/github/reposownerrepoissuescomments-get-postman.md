{
  "info": {
    "name": "Github Get Repos Owner Repo Issues Comments",
    "_postman_id": "d6de7568-92ba-4490-bebc-cb86704852a1",
    "description": "List comments in a repository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "bf4dfc51-212d-4c88-b4dc-208ef49aea68",
          "name": "list-comments-in-a-repository",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/issues/comments"
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
              "id": "cafccd5f-cb37-4c78-8946-1f1d441ec64e"
            }
          ]
        }
      ]
    }
  ]
}
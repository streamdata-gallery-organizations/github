{
  "info": {
    "name": "Github Get Teams Team Repos",
    "_postman_id": "0cecc459-7ddc-4006-8dff-9bfafe0cc00a",
    "description": "List team repos",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "718bad59-06c8-437f-a363-f0b9d73a9162",
          "name": "list-team-repos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "teams/:teamId/repos"
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
                  "id": "teamId",
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
            "description": "List team repos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a37283c0-4984-4ffd-bb76-aafc8f8c3c1c"
            }
          ]
        }
      ]
    }
  ]
}
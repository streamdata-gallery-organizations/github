{
  "info": {
    "name": "Github Get Users Username Repos",
    "_postman_id": "b2e5b953-f237-4705-a03a-75db31f65f55",
    "description": "List public repositories for the specified user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "e59946a5-bde5-4e7b-9c00-43a4d6408a36",
          "name": "list-public-repositories-for-the-specified-user",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/repos"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "username",
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
            "description": "List public repositories for the specified user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d8449c8-a9e5-487d-a309-cdb72d6c2d09"
            }
          ]
        }
      ]
    }
  ]
}
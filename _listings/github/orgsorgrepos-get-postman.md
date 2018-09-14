{
  "info": {
    "name": "Github Get Orgs Org Repos",
    "_postman_id": "5367a7e4-f473-41b5-add4-1d4e24ffb28f",
    "description": "List repositories for the specified org.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "orgs",
      "item": [
        {
          "id": "bd919f7d-fb09-4940-b6c0-ccc1fd0a8c13",
          "name": "list-repositories-for-the-specified-org",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "orgs/:org/repos"
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
                  "id": "org",
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
            "description": "List repositories for the specified org"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5cc4aa23-f751-4e46-a4c1-be817fd8aac4"
            }
          ]
        }
      ]
    }
  ]
}
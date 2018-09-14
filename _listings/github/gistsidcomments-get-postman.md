{
  "info": {
    "name": "Github Get Gists  Comments",
    "_postman_id": "177b27e4-ef1b-4ba9-8fcd-faab770ca0a8",
    "description": "List comments on a gist.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "gists",
      "item": [
        {
          "id": "972b6ade-4430-48f7-9f71-a2e6c3d56113",
          "name": "list-comments-on-a-gist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "gists/:id/comments"
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
                  "id": "id",
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
            "description": "List comments on a gist"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9cb20c4-b839-4212-9912-32668cc87842"
            }
          ]
        }
      ]
    }
  ]
}
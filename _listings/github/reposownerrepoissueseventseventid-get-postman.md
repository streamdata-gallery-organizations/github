{
  "info": {
    "name": "Github Get Repos Owner Repo Issues Events Event",
    "_postman_id": "b1891187-eeb6-4f9f-b2d4-dd31e66a927c",
    "description": "Get a single event.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "5d5a4473-b552-488b-8ebd-631ee208529d",
          "name": "get-a-single-event",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/issues/events/:eventId"
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
                  "id": "eventId",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Get a single event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "191f0447-a9c9-4422-a5b3-0a0f6d274fe3"
            }
          ]
        }
      ]
    }
  ]
}
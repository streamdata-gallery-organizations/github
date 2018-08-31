{
  "info": {
    "name": "Github Get Users Username Events Orgs Org",
    "_postman_id": "a9de0952-18c7-4d52-beb6-73928afec1b1",
    "description": "This is the user's organization dashboard. You must be authenticated as the user to view this.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "dd713e15-24fe-40a5-be05-e2607a83f7f1",
          "name": "this-is-the-users-organization-dashboard-you-must-be-authenticated-as-the-user-to-view-this",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/events/orgs/:org"
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
                  "id": "org",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "This is the user's organization dashboard"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc8c7850-5f49-4a33-bf77-9ebd09583a31"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Github Delete Orgs Org Members Username",
    "_postman_id": "63bed392-a430-4dcb-844d-6c55f47aeb92",
    "description": "Remove a member.\nRemoving a user from this list will remove them from all teams and they\nwill no longer have any access to the organization's repositories.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "orgs",
      "item": [
        {
          "id": "66d1a220-6c45-46de-8617-07985a161a3a",
          "name": "remove-a-memberremoving-a-user-from-this-list-will-remove-them-from-all-teams-and-theywill-no-longer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "orgs/:org/members/:username"
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
            "method": "DELETE",
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
            "description": "Remove a member"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5463b1a6-1535-4021-bc3d-4893d8393d62"
            }
          ]
        }
      ]
    }
  ]
}
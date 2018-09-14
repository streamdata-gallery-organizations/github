{
  "info": {
    "name": "Github Delete Orgs Org Public Members Username",
    "_postman_id": "ecad0d61-7d63-488f-abce-4b53a88428f1",
    "description": "Conceal a user's membership.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "orgs",
      "item": [
        {
          "id": "c30cd1f3-10e6-40bc-8d84-28cb9c502a83",
          "name": "conceal-a-users-membership",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "orgs/:org/public_members/:username"
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
            "description": "Conceal a user's membership"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe36213c-03d7-4ef9-bcec-9599391dffba"
            }
          ]
        }
      ]
    }
  ]
}
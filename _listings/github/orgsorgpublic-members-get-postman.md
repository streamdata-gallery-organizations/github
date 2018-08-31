{
  "info": {
    "name": "Github Get Orgs Org Public Members",
    "_postman_id": "2fbb7e3f-763f-45c3-bfde-ed4fdc3f538f",
    "description": "Public members list.\nMembers of an organization can choose to have their membership publicized\nor not.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "orgs",
      "item": [
        {
          "id": "4c713406-cd26-472e-addf-8180f30fecbb",
          "name": "public-members-listmembers-of-an-organization-can-choose-to-have-their-membership-publicizedor-not",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "orgs/:org/public_members"
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
            "description": "Public members list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c647dcc8-9d8a-4b25-8adb-0297bf389709"
            }
          ]
        }
      ]
    }
  ]
}
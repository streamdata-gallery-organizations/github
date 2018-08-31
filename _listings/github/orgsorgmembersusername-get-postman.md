{
  "info": {
    "name": "Github Get Orgs Org Members Username",
    "_postman_id": "0124d7d4-ae10-437e-bc33-c5c4dee25e1a",
    "description": "Check if a user is, publicly or privately, a member of the organization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "orgs",
      "item": [
        {
          "id": "4b4d8183-8ff2-429b-95f1-054b53b40c24",
          "name": "check-if-a-user-is-publicly-or-privately-a-member-of-the-organization",
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
            "description": "Check if a user is, publicly or privately, a member of the organization"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "599d3c3f-7e1c-4660-887e-ae080f48c02d"
            }
          ]
        }
      ]
    }
  ]
}
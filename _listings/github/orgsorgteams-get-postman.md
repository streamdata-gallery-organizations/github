{
  "info": {
    "name": "Github Get Orgs Org Teams",
    "_postman_id": "776ac1b9-9387-4a55-afc6-0959dbe1e4f0",
    "description": "List teams.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "orgs",
      "item": [
        {
          "id": "f215d741-4b86-4e3f-be0c-8e48ff265466",
          "name": "list-teams",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "orgs/:org/teams"
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
            "description": "List teams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79c8d7ef-7e96-41dc-99e3-cdfa55bc24b3"
            }
          ]
        }
      ]
    }
  ]
}
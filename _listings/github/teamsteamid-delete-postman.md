{
  "info": {
    "name": "Github Delete Teams Team",
    "_postman_id": "02346e9b-ce1f-44b1-91b5-981ba2dd1ba1",
    "description": "Delete team.\nIn order to delete a team, the authenticated user must be an owner of the\norg that the team is associated with.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "450d49d6-b654-420b-b457-e52cb2512ac3",
          "name": "delete-teamin-order-to-delete-a-team-the-authenticated-user-must-be-an-owner-of-theorg-that-the-team",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "teams/:teamId"
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
                  "id": "teamId",
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
            "description": "Delete team"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7dbadb5d-3fcc-4507-bc4b-0ab2bbadc16e"
            }
          ]
        }
      ]
    }
  ]
}
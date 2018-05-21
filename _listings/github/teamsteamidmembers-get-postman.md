{
  "info": {
    "name": "Github Get Teams Team Members",
    "_postman_id": "915b8621-4bff-4102-88b4-8e5bbf598774",
    "description": "List team members.\nIn order to list members in a team, the authenticated user must be a member\nof the team.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "5528aaa7-409b-4aea-ad7a-937baf8a8df5",
          "name": "list-team-membersin-order-to-list-members-in-a-team-the-authenticated-user-must-be-a-memberof-the-te",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "teams/:teamId/members"
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
            "description": "List team members"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60b06e4b-2bb5-4c68-a115-85a751e82ea4"
            }
          ]
        }
      ]
    }
  ]
}
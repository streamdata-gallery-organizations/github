{
  "info": {
    "name": "Github Get Teams Team Memberships Username",
    "_postman_id": "51f1f985-ac0e-4f39-a4cf-6c2dcab61d56",
    "description": "Get team membership.\nIn order to get a user's membership with a team, the authenticated user must be a member of the team or an owner of the team's organization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "0d2603a4-0cad-41cc-99f1-bd39b26e7e3f",
          "name": "get-team-membershipin-order-to-get-a-users-membership-with-a-team-the-authenticated-user-must-be-a-m",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "teams/:teamId/memberships/:username"
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
            "description": "Get team membership"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a3aaeea1-7266-4bfc-9de2-a0d3ac500c20"
            }
          ]
        }
      ]
    }
  ]
}
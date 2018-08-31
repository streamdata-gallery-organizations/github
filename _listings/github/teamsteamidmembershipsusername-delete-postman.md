{
  "info": {
    "name": "Github Delete Teams Team Memberships Username",
    "_postman_id": "9eca4c56-9275-4198-887d-1d274c7e9b37",
    "description": "Remove team membership.\nIn order to remove a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with. NOTE: This does not delete the user, it just removes their membership from the team.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "f9e0624b-78ec-4b4a-9a88-268d842a48bd",
          "name": "remove-team-membershipin-order-to-remove-a-membership-between-a-user-and-a-team-the-authenticated-us",
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
            "description": "Remove team membership"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8161525-b3ee-446d-b2cb-418b44a6a7c1"
            }
          ]
        }
      ]
    }
  ]
}
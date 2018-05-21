{
  "info": {
    "name": "Github Put Teams Team Memberships Username",
    "_postman_id": "53dac9ed-3321-4e09-b99e-85b1dfdb7403",
    "description": "Add team membership.\nIn order to add a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with.\n\nIf the user is already a part of the team's organization (meaning they're on at least one other team in the organization), this endpoint will add the user to the team.\n\nIf the user is completely unaffiliated with the team's organization (meaning they're on none of the organization's teams), this endpoint will send an invitation to the user via email. This newly-created membership will be in the 'pending' state until the user accepts the invitation, at which point the membership will transition to the 'active' state and the user will be added as a member of the team.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "0d7fb67c-41aa-4684-9b9f-36fa959fa650",
          "name": "add-team-membershipin-order-to-add-a-membership-between-a-user-and-a-team-the-authenticated-user-mus",
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
            "method": "PUT",
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
            "description": "Add team membership"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c8b0496-3bec-41db-a408-c8a4cc8f6b6a"
            }
          ]
        }
      ]
    }
  ]
}
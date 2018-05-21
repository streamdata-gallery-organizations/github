{
  "info": {
    "name": "Github Delete Teams Team Members Username",
    "_postman_id": "abe44495-5e7e-4d14-971c-a559ad074350",
    "description": "The \"Remove team member\" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Remove team membership API instead. It allows you to remove both active and pending memberships.\n\nRemove team member.\nIn order to remove a user from a team, the authenticated user must have 'admin'\npermissions to the team or be an owner of the org that the team is associated\nwith.\nNOTE This does not delete the user, it just remove them from the team.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "a8f41383-3893-4c76-b34c-e882c8f06357",
          "name": "the-remove-team-member-api-is-deprecated-and-is-scheduled-for-removal-in-the-next-major-version-of-t",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "teams/:teamId/members/:username"
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
            "description": "The \"Remove team member\" API is deprecated and is scheduled for removal in the next major version of the API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad5a19b3-e539-4e07-bd92-fbcdc026d51b"
            }
          ]
        }
      ]
    }
  ]
}
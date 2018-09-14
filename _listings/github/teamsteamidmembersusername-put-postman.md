{
  "info": {
    "name": "Github Put Teams Team Members Username",
    "_postman_id": "5ea4ac0f-f04e-4179-ace6-e9bda1a1be4d",
    "description": "The API (described below) is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Add team membership API instead. It allows you to invite new organization members to your teams.\n\nAdd team member.\nIn order to add a user to a team, the authenticated user must have 'admin'\npermissions to the team or be an owner of the org that the team is associated\nwith.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "b4ca1403-0a96-4fc3-a0ac-c2ccaf2fdb71",
          "name": "the-api-described-below-is-deprecated-and-is-scheduled-for-removal-in-the-next-major-version-of-the-",
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
            "description": "The API (described below) is deprecated and is scheduled for removal in the next major version of the API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c815afe7-588c-4351-bca5-f224223070e0"
            }
          ]
        }
      ]
    }
  ]
}
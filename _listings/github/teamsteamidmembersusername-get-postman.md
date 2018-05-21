{
  "info": {
    "name": "Github Get Teams Team Members Username",
    "_postman_id": "c60786f4-9244-4f03-972a-037558b8129b",
    "description": "The \"Get team member\" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Get team membership API instead. It allows you to get both active and pending memberships.\n\nGet team member.\nIn order to get if a user is a member of a team, the authenticated user mus\nbe a member of the team.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "973f21f3-7b8f-4fea-aa23-c3e7f83c9ca5",
          "name": "the-get-team-member-api-is-deprecated-and-is-scheduled-for-removal-in-the-next-major-version-of-the-",
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
            "description": "The \"Get team member\" API is deprecated and is scheduled for removal in the next major version of the API"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c84f5e4-1bc4-484c-b431-716923080463"
            }
          ]
        }
      ]
    }
  ]
}
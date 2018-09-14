{
  "info": {
    "name": "Github Put Teams Team Repos Org Repo",
    "_postman_id": "95d392a8-8dde-4839-8cf9-db8da4cd6458",
    "description": "In order to add a repository to a team, the authenticated user must be an owner of the org that the team is associated with. Also, the repository must be owned by the organization, or a direct fork of a repository owned by the organization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "bdabb598-f167-4682-84a4-175fed3500f6",
          "name": "in-order-to-add-a-repository-to-a-team-the-authenticated-user-must-be-an-owner-of-the-org-that-the-t",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "teams/:teamId/repos/:org/:repo"
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
                  "id": "repo",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "teamId",
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
            "description": "In order to add a repository to a team, the authenticated user must be an owner of the org that the team is associated with"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2bb3ec9-ffd6-4f05-8348-513eda578832"
            }
          ]
        }
      ]
    }
  ]
}
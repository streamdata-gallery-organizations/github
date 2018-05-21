{
  "info": {
    "name": "Github Delete Teams Team Repos Owner Repo",
    "_postman_id": "1cf86883-8a2b-41f5-8853-9503b1974552",
    "description": "In order to remove a repository from a team, the authenticated user must be an owner of the org that the team is associated with. NOTE: This does not delete the repository, it just removes it from the team.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "teams",
      "item": [
        {
          "id": "99e2be14-23a9-4d8c-8c95-bad9e5511233",
          "name": "in-order-to-remove-a-repository-from-a-team-the-authenticated-user-must-be-an-owner-of-the-org-that-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "teams/:teamId/repos/:owner/:repo"
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
                  "id": "owner",
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
            "description": "In order to remove a repository from a team, the authenticated user must be an owner of the org that the team is associated with"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "735f674d-c693-41f9-b76b-cb6c299a4a0a"
            }
          ]
        }
      ]
    }
  ]
}
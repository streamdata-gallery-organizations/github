{
  "info": {
    "name": "Github Delete Repos Owner Repo Git Refs Ref",
    "_postman_id": "dbc8a4fc-fde7-42bf-a640-6597932cd4f2",
    "description": "Delete a Reference\nExample: Deleting a branch: DELETE /repos/octocat/Hello-World/git/refs/heads/feature-a \nExample: Deleting a tag:        DELETE /repos/octocat/Hello-World/git/refs/tags/v1.0",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "60b011e8-9cda-4e46-9d8e-2bd0c173ff85",
          "name": "delete-a-referenceexample-deleting-a-branch-delete-reposoctocathelloworldgitrefsheadsfeaturea-exampl",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/git/refs/:ref"
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
                  "id": "ref",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "repo",
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
            "description": "Delete a Reference\nExample: Deleting a branch: DELETE /repos/octocat/Hello-World/git/refs/heads/feature-a \nExample: Deleting a tag:        DELETE /repos/octocat/Hello-World/git/refs/tags/v1"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e03867c-98fc-4b2e-9e1f-1f11a822cd74"
            }
          ]
        }
      ]
    }
  ]
}
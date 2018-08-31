{
  "info": {
    "name": "Github Delete Repos Owner Repo",
    "_postman_id": "d972e463-8e01-4809-bcf0-233fca7eaf07",
    "description": "Delete a Repository.\nDeleting a repository requires admin access. If OAuth is used, the delete_repo\nscope is required.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "33454e4b-e091-432e-bdb1-c36f100531cc",
          "name": "delete-a-repositorydeleting-a-repository-requires-admin-access-if-oauth-is-used-the-delete-reposcope",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo"
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
            "description": "Delete a Repository"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71fbc5d1-13fd-4d8d-a6aa-86e32ef31df6"
            }
          ]
        }
      ]
    }
  ]
}
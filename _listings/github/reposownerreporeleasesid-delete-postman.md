{
  "info": {
    "name": "Github Delete Repos Owner Repo Releases",
    "_postman_id": "89aea905-2f42-4a8d-b22e-cf37de8ffc08",
    "description": "Users with push access to the repository can delete a release.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "26bcbd91-a52f-450f-b454-b207c98bb794",
          "name": "users-with-push-access-to-the-repository-can-delete-a-release",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/releases/:id"
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
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Users with push access to the repository can delete a release"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4db39b66-2149-4da9-9127-96a78fa70376"
            }
          ]
        }
      ]
    }
  ]
}
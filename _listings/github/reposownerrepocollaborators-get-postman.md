{
  "info": {
    "name": "Github Get Repos Owner Repo Collaborators",
    "_postman_id": "7fc6e5ca-d4a1-483b-9a92-b1de878e9863",
    "description": "List.\nWhen authenticating as an organization owner of an organization-owned\nrepository, all organization owners are included in the list of\ncollaborators. Otherwise, only users with access to the repository are\nreturned in the collaborators list.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "ecdc6fad-3418-4c10-b303-8fad5b439acb",
          "name": "listwhen-authenticating-as-an-organization-owner-of-an-organizationownedrepository-all-organization-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/collaborators"
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
            "description": "List"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50d31811-a49d-44d0-bb67-5ad971fa9b48"
            }
          ]
        }
      ]
    }
  ]
}
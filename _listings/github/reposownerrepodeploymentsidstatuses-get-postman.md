{
  "info": {
    "name": "Github Get Repos Owner Repo Deployments  Statuses",
    "_postman_id": "2f9eb1b2-9167-4b68-95eb-ecc71f22c30d",
    "description": "Users with pull access can view deployment statuses for a deployment",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "7eaddda9-b84b-48cb-8ad8-2765248f15bc",
          "name": "users-with-pull-access-can-view-deployment-statuses-for-a-deployment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/deployments/:id/statuses"
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
            "description": "Users with pull access can view deployment statuses for a deployment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf997a42-ea61-4fac-a20b-7dbea7e8db44"
            }
          ]
        }
      ]
    }
  ]
}
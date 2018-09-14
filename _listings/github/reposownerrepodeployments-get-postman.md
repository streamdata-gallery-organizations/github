{
  "info": {
    "name": "Github Get Repos Owner Repo Deployments",
    "_postman_id": "b68595a1-cb16-43eb-a57b-15a772edd2fb",
    "description": "Users with pull access can view deployments for a repository",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "48c52708-8891-4302-a8e8-818a6d842f0a",
          "name": "users-with-pull-access-can-view-deployments-for-a-repository",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/deployments"
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
            "description": "Users with pull access can view deployments for a repository"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4560405e-11aa-46d4-bf7e-a6c8fc2cd8e5"
            }
          ]
        }
      ]
    }
  ]
}
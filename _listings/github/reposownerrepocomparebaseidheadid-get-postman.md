{
  "info": {
    "name": "Github Get Repos Owner Repo Compare Base ... Head",
    "_postman_id": "6f0458ad-6dbc-4b8a-993c-e14e712cf221",
    "description": "Compare two commits",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "c8f07c95-044c-49fe-a623-b270e915ad83",
          "name": "compare-two-commits",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/compare/:baseId...:headId"
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
                  "id": "baseId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "headId",
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
            "description": "Compare two commits"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cabe4158-2012-47f6-ad93-5e7f378f80ce"
            }
          ]
        }
      ]
    }
  ]
}
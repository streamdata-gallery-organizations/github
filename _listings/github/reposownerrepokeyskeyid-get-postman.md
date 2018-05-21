{
  "info": {
    "name": "Github Get Repos Owner Repo Keys Key",
    "_postman_id": "438554ca-6904-4c19-afd3-1b9fb247490c",
    "description": "Get a key",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "9f574499-8e9d-46c9-9b4b-4fc7e8dd63b2",
          "name": "get-a-key",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/keys/:keyId"
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
                  "id": "keyId",
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
            "description": "Get a key"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "860ced2a-9d59-43bb-ade4-f198b516be91"
            }
          ]
        }
      ]
    }
  ]
}
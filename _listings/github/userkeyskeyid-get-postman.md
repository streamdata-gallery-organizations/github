{
  "info": {
    "name": "Github Get User Keys Key",
    "_postman_id": "0161b5b5-881d-405a-8eaf-b8c9858393ae",
    "description": "Get a single public key.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "user",
      "item": [
        {
          "id": "2f66b9dd-d29c-47ce-81fd-bb1861d6c1f2",
          "name": "get-a-single-public-key",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "user/keys/:keyId"
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
            "description": "Get a single public key"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf05ca03-be40-4b68-887b-f001661b7b04"
            }
          ]
        }
      ]
    }
  ]
}
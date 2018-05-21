{
  "info": {
    "name": "Github Get Repos Owner Repo Contributors",
    "_postman_id": "67cfcfbc-8e2e-4726-96ea-4ae898d75518",
    "description": "Get list of contributors.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "19cb2601-dded-466f-855e-576384ac6de4",
          "name": "get-list-of-contributors",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/contributors"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "anon",
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
            "description": "Get list of contributors"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97895039-0d96-4489-8389-390717cd6ed6"
            }
          ]
        }
      ]
    }
  ]
}
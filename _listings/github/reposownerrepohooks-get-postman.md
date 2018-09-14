{
  "info": {
    "name": "Github Get Repos Owner Repo Hooks",
    "_postman_id": "db6ea219-6fff-4176-9840-6ee841a2732c",
    "description": "Get list of hooks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "86506c58-806f-4c5b-b0c1-986e1d1a380b",
          "name": "get-list-of-hooks",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/hooks"
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
            "description": "Get list of hooks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65dcb6ad-691a-4b6e-b1eb-fb59fd656460"
            }
          ]
        }
      ]
    }
  ]
}
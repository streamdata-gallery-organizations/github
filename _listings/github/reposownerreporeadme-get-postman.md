{
  "info": {
    "name": "Github Get Repos Owner Repo Readme",
    "_postman_id": "9ae6d7d1-5c95-4f7a-acd6-94fafd1a3543",
    "description": "Get the README.\nThis method returns the preferred README for a repository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "6846e02b-cc3b-4afc-9502-eb2489945614",
          "name": "get-the-readmethis-method-returns-the-preferred-readme-for-a-repository",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/readme"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ref",
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
            "description": "Get the README"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "593c93fa-242e-4e55-a27c-5c0e8919c7d8"
            }
          ]
        }
      ]
    }
  ]
}
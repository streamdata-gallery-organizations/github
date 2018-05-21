{
  "info": {
    "name": "Github Get Repos Owner Repo Languages",
    "_postman_id": "9893f8d6-8ac0-4110-bfa6-4cebb28cd540",
    "description": "List languages.\nList languages for the specified repository. The value on the right of a\nlanguage is the number of bytes of code written in that language.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "34e046f0-9a25-4eaf-8c41-c34848f66b3f",
          "name": "list-languageslist-languages-for-the-specified-repository-the-value-on-the-right-of-alanguage-is-the",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/languages"
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
            "description": "List languages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc18a08f-e45c-4346-a4d0-5d770da45d40"
            }
          ]
        }
      ]
    }
  ]
}
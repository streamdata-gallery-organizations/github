{
  "info": {
    "name": "Github Get Repos Owner Repo Releases",
    "_postman_id": "d05320be-d2f7-41c6-84c9-4d50029b5310",
    "description": "Users with push access to the repository will receive all releases (i.e., published releases and draft releases). Users with pull access will receive published releases only",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "1b9c13af-dab3-40ee-b332-9a11f20fe066",
          "name": "users-with-push-access-to-the-repository-will-receive-all-releases-ie-published-releases-and-draft-r",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/releases"
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
            "description": "Users with push access to the repository will receive all releases (i"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d7674c8-df7e-4b34-8e39-c1819c20a8cf"
            }
          ]
        }
      ]
    }
  ]
}
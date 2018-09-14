{
  "info": {
    "name": "Github Get Repos Owner Repo Milestones Number Labels",
    "_postman_id": "1a589683-bf1b-43ef-b5f5-917e50c6dba3",
    "description": "Get labels for every issue in a milestone.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "1de99ace-712f-4459-ae63-2b6f4d2ad486",
          "name": "get-labels-for-every-issue-in-a-milestone",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/milestones/:number/labels"
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
                  "id": "number",
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
            "description": "Get labels for every issue in a milestone"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cce753bc-7204-4269-992c-1a17f2efeaa9"
            }
          ]
        }
      ]
    }
  ]
}
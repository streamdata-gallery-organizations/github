{
  "info": {
    "name": "GitHub",
    "_postman_id": "5f344d26-2795-4729-a54d-54bb756e1e9f",
    "description": "GitHub is the best place to share code with friends, co-workers, classmates, and complete strangers. Over 24 million people use GitHub to build amazing things together across 67 million repositories. With the collaborative features of GitHub.com and GitHub Business, it has never been easier for individuals and teams to write faster, better code.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "f7bae4e8-d968-41b6-a370-900471489a4f",
          "name": "check-assigneeyou-may-also-check-to-see-if-a-particular-user-is-an-assignee-for-a-repository",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/assignees/:assignee"
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
                  "id": "assignee",
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
            "description": "Check assignee"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f81248d5-9082-4862-8612-08bd0eff6d2c"
            }
          ]
        }
      ]
    }
  ]
}
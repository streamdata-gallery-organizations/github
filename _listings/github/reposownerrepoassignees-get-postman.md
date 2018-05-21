{
  "info": {
    "name": "GitHub",
    "_postman_id": "469f22b7-1690-436e-9440-304a494e0dfe",
    "description": "GitHub is the best place to share code with friends, co-workers, classmates, and complete strangers. Over 24 million people use GitHub to build amazing things together across 67 million repositories. With the collaborative features of GitHub.com and GitHub Business, it has never been easier for individuals and teams to write faster, better code.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "9d395297-1f21-4302-810c-36071087f225",
          "name": "list-assigneesthis-call-lists-all-the-available-assignees-owner--collaborators-to-whichissues-may-be",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/assignees"
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
            "description": "List assignees"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c420c99b-2fa5-48f3-96e1-99a7e6399663"
            }
          ]
        }
      ]
    }
  ]
}
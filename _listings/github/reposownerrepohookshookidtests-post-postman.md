{
  "info": {
    "name": "Github Add Repos Owner Repo Hooks Hook Tests",
    "_postman_id": "3e833eb1-2d3c-4bbb-9384-643baafaa0cf",
    "description": "Test a push hook.\nThis will trigger the hook with the latest push to the current repository\nif the hook is subscribed to push events. If the hook is not subscribed\nto push events, the server will respond with 204 but no test POST will\nbe generated.\nNote: Previously /repos/:owner/:repo/hooks/:id/tes",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "ec20d9a8-6912-4596-af2f-f9abe5e45ccc",
          "name": "test-a-push-hookthis-will-trigger-the-hook-with-the-latest-push-to-the-current-repositoryif-the-hook",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/hooks/:hookId/tests"
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
                  "id": "hookId",
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
            "method": "POST",
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
            "description": "Test a push hook"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cebf57cb-a233-475b-b557-8addc16e582b"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Github Get Repos Owner Repo Stats Commit Activity",
    "_postman_id": "346e209a-f49e-4635-b7f4-f9d7741a1385",
    "description": "Get the last year of commit activity data.\nReturns the last year of commit activity grouped by week. The days array\nis a group of commits per day, starting on Sunday.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "95da2c15-079a-4100-a3e7-a754708a388d",
          "name": "get-the-last-year-of-commit-activity-datareturns-the-last-year-of-commit-activity-grouped-by-week-th",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/stats/commit_activity"
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
            "description": "Get the last year of commit activity data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cab3847a-80fc-49f4-b40c-a7eb2e55f4bd"
            }
          ]
        }
      ]
    }
  ]
}
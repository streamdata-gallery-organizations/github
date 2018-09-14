{
  "info": {
    "name": "Github Get Repos Owner Repo Commits Ref Status",
    "_postman_id": "81fd0038-ff58-4fe3-b1e8-2c28a5748941",
    "description": "Get the combined Status for a specific Ref\nThe Combined status endpoint is currently available for developers to preview. During the preview period, the API may change without advance notice. Please see the blog post for full details.\nTo access this endpoint during the preview period, you must provide a custom media type in the Accept header:\napplication/vnd.github.she-hulk-preview+json",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "b20136ae-928f-4668-b543-dd8a5280dfcc",
          "name": "get-the-combined-status-for-a-specific-refthe-combined-status-endpoint-is-currently-available-for-de",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/commits/:ref/status"
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
                  "id": "ref",
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
            "description": "Get the combined Status for a specific Ref\nThe Combined status endpoint is currently available for developers to preview"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e4c8d5f-bebb-4fa8-ab52-685dd5c59499"
            }
          ]
        }
      ]
    }
  ]
}
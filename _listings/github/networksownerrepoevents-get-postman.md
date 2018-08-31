{
  "info": {
    "name": "Github Get Networks Owner Repo Events",
    "_postman_id": "99abd2d8-7a94-47e3-ba37-a7e618c7e8c1",
    "description": "List public events for a network of repositories.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "networks",
      "item": [
        {
          "id": "8cd44661-2094-4ef7-8cdf-9ea9444db8d6",
          "name": "list-public-events-for-a-network-of-repositories",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "networks/:owner/:repo/events"
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
            "description": "List public events for a network of repositories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92e40d75-4c34-4a96-aede-be649b6c8f03"
            }
          ]
        }
      ]
    }
  ]
}
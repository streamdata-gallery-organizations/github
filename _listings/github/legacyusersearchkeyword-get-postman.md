{
  "info": {
    "name": "Github Get Legacy User Search Keyword",
    "_postman_id": "a5a64321-7554-43d2-8911-6d494948688b",
    "description": "Find users by keyword.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "legacy",
      "item": [
        {
          "id": "c42591d5-31cb-4c98-b3ff-9d3187c63110",
          "name": "find-users-by-keyword",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "legacy/user/search/:keyword"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "order",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "start_page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "keyword",
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
            "description": "Find users by keyword"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27213382-d576-44af-9760-a8b9440fb5e2"
            }
          ]
        }
      ]
    }
  ]
}
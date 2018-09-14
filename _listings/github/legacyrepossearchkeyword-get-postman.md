{
  "info": {
    "name": "Github Get Legacy Repos Search Keyword",
    "_postman_id": "ce76a97a-e39b-4fa0-b8e1-b632e25db5db",
    "description": "Find repositories by keyword. Note, this legacy method does not follow the v3 pagination pattern. This method returns up to 100 results per page and pages can be fetched using the start_page parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "legacy",
      "item": [
        {
          "id": "f57ff3db-eda0-45d0-9882-bf337de453bf",
          "name": "find-repositories-by-keyword-note-this-legacy-method-does-not-follow-the-v3-pagination-pattern-this-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "legacy/repos/search/:keyword"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "language",
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
            "description": "Find repositories by keyword"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dab89141-2fce-44b7-a2af-06bd83214f7a"
            }
          ]
        }
      ]
    }
  ]
}
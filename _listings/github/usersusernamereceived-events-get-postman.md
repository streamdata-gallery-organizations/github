{
  "info": {
    "name": "Github Get Users Username Received Events",
    "_postman_id": "13517184-b3d2-4dc6-a88f-9ffb7ad101ad",
    "description": "These are events that you'll only see public events.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "2133296a-8196-4510-a29c-eb7139135e67",
          "name": "these-are-events-that-youll-only-see-public-events",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/received_events"
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
                  "id": "username",
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
            "description": "These are events that you'll only see public events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb7f14c8-84c2-48e2-98ac-63ab7fe87c47"
            }
          ]
        }
      ]
    }
  ]
}
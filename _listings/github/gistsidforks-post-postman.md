{
  "info": {
    "name": "Github Add Gists  Forks",
    "_postman_id": "077f81b5-0f9b-42d5-b3b2-fd84915d0977",
    "description": "Fork a gist.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "gists",
      "item": [
        {
          "id": "bddab4cb-5e4a-4e13-ad87-f61143c5f314",
          "name": "fork-a-gist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "gists/:id/forks"
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
                  "id": "id",
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
            "description": "Fork a gist"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9457b948-2e8f-4085-9111-10d7574b4d01"
            }
          ]
        }
      ]
    }
  ]
}
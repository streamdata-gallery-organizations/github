{
  "info": {
    "name": "Github Delete Gists  Comments Comment",
    "_postman_id": "e3246d55-5b99-4cf1-80de-cce43754e7da",
    "description": "Delete a comment.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "gists",
      "item": [
        {
          "id": "d3ba360f-acd7-4549-820b-fbb0c49915b7",
          "name": "delete-a-comment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "gists/:id/comments/:commentId"
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
                  "id": "commentId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
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
            "description": "Delete a comment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3b40efd-f042-4935-8bdb-329bb80837b4"
            }
          ]
        }
      ]
    }
  ]
}
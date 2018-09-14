{
  "info": {
    "name": "Github Delete User Keys Key",
    "_postman_id": "af58388d-9c78-4ba4-8f75-1fdf84e50ce7",
    "description": "Delete a public key. Removes a public key. Requires that you are authenticated via Basic Auth or via OAuth with at least admin:public_key scope.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "user",
      "item": [
        {
          "id": "610b0b4a-334a-4409-9a1d-89988402ec32",
          "name": "delete-a-public-key-removes-a-public-key-requires-that-you-are-authenticated-via-basic-auth-or-via-o",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "user/keys/:keyId"
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
                  "id": "keyId",
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
            "description": "Delete a public key"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43d79fd1-0e41-440d-8593-9aad667335c5"
            }
          ]
        }
      ]
    }
  ]
}
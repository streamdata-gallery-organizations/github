{
  "info": {
    "name": "Github Get Users Username Keys",
    "_postman_id": "b6978c32-d353-4ea4-b23d-8a482f1e1ff3",
    "description": "List public keys for a user.\nLists the verified public keys for a user. This is accessible by anyone.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "ac6b8163-ad0c-4700-87bc-a4015400225c",
          "name": "list-public-keys-for-a-userlists-the-verified-public-keys-for-a-user-this-is-accessible-by-anyone",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/keys"
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
            "description": "List public keys for a user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "516f49a8-981c-47c9-97a8-b3a752e266cc"
            }
          ]
        }
      ]
    }
  ]
}
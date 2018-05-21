{
  "info": {
    "name": "Github Get User Keys",
    "_postman_id": "b1623a4c-e894-41ba-a9e5-40708cac9a77",
    "description": "List your public keys.\nLists the current user's keys. Management of public keys via the API requires\nthat you are authenticated through basic auth, or OAuth with the 'user', 'write:public_key' scopes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "user",
      "item": [
        {
          "id": "6f69c324-8b90-4145-ab99-0201242be0e4",
          "name": "list-your-public-keyslists-the-current-users-keys-management-of-public-keys-via-the-api-requiresthat",
          "request": {
            "url": "http://api.github.com/user/keys?access_token=%7B%7D",
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
            "description": "List your public keys"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d43a83ba-2263-401b-9997-7901b2a36ff8"
            }
          ]
        }
      ]
    }
  ]
}
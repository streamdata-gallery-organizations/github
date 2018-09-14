{
  "info": {
    "name": "Github Get Users",
    "_postman_id": "383c1960-4ae9-4e8e-95b1-7289b481b5a2",
    "description": "Get all users.\nThis provides a dump of every user, in the order that they signed up for GitHub.\nNote: Pagination is powered exclusively by the since parameter. Use the Link\nheader to get the URL for the next page of users.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "b81cf101-d2b4-441a-9719-18a45099e3c5",
          "name": "get-all-usersthis-provides-a-dump-of-every-user-in-the-order-that-they-signed-up-for-githubnote-pagi",
          "request": {
            "url": "http://api.github.com/users?access_token=%7B%7D&since=%7B%7D",
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
            "description": "Get all users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a6b0d9d-5907-43f0-a509-406cea225454"
            }
          ]
        }
      ]
    }
  ]
}
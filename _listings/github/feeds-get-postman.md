{
  "info": {
    "name": "Github Get Feeds",
    "_postman_id": "d8526e2a-b725-4573-a3dd-583e42997aee",
    "description": "List Feeds.\nGitHub provides several timeline resources in Atom format. The Feeds API\n lists all the feeds available to the authenticating user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "feeds",
      "item": [
        {
          "id": "2ee7c7fd-dfb8-4609-b271-4e86e3048452",
          "name": "list-feedsgithub-provides-several-timeline-resources-in-atom-format-the-feeds-api-lists-all-the-feed",
          "request": {
            "url": "http://api.github.com/feeds?access_token=%7B%7D",
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
            "description": "List Feeds"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab1dc452-dcd7-48aa-bed7-c44f9394c683"
            }
          ]
        }
      ]
    }
  ]
}
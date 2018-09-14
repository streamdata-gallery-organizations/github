{
  "info": {
    "name": "Github Get Users Username Events",
    "_postman_id": "be69751c-d57c-46ca-814d-4a1baa447073",
    "description": "If you are authenticated as the given user, you will see your private events. Otherwise, you'll only see public events.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "d44c1f15-8784-491e-be0b-3ebd7c9f65ee",
          "name": "if-you-are-authenticated-as-the-given-user-you-will-see-your-private-events-otherwise-youll-only-see",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "users/:username/events"
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
            "description": "If you are authenticated as the given user, you will see your private events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89675c75-40fb-42d3-95aa-4cbabf3ae341"
            }
          ]
        }
      ]
    }
  ]
}
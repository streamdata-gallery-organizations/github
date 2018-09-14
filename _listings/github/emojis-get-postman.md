{
  "info": {
    "name": "Github Get Emojis",
    "_postman_id": "77817fc8-27b5-4903-85a5-8f55d5394c47",
    "description": "Lists all the emojis available to use on GitHub.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "emojis",
      "item": [
        {
          "id": "d1bece83-0a74-4890-856f-228b0930da6e",
          "name": "lists-all-the-emojis-available-to-use-on-github",
          "request": {
            "url": "http://api.github.com/emojis?access_token=%7B%7D",
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
            "description": "Lists all the emojis available to use on GitHub"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37522dac-40ae-477c-8559-07596608e7c1"
            }
          ]
        }
      ]
    }
  ]
}
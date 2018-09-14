{
  "info": {
    "name": "Github Get Gists",
    "_postman_id": "2f4297d1-c6e2-4381-9d33-7915e11691f0",
    "description": "List the authenticated user's gists or if called anonymously, this will\nreturn all public gists.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Emojis",
      "item": [
        {
          "id": "5eb624ad-0d1c-4d23-b3b1-b41e717beedd",
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
            "description": "Lists all the emojis available to use on GitHub."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f291d4f-7534-4f83-b626-e8fceb32555a"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "a3fe24fd-c092-4457-a6f8-01944dba9a72",
          "name": "list-public-events",
          "request": {
            "url": "http://api.github.com/events?access_token=%7B%7D",
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
            "description": "List public events."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9976af9f-f57f-4c43-9702-ebbf47240710"
            }
          ]
        }
      ]
    },
    {
      "name": "Feeds",
      "item": [
        {
          "id": "82141c84-5a4a-42c6-b9ce-264f5c1b20fb",
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
            "description": "List Feeds.\nGitHub provides several timeline resources in Atom format. The Feeds API\n lists all the feeds available to the authenticating user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a31a87a-e398-4766-af70-5bfbc5f151f8"
            }
          ]
        }
      ]
    },
    {
      "name": "Gists",
      "item": [
        {
          "id": "03a975cf-d87b-4199-95c7-0fa81f66e94d",
          "name": "list-the-authenticated-users-gists-or-if-called-anonymously-this-willreturn-all-public-gists",
          "request": {
            "url": "http://api.github.com/gists?access_token=%7B%7D&since=%7B%7D",
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
            "description": "List the authenticated user's gists or if called anonymously, this will\nreturn all public gists."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f099222-7087-4529-80fd-df4f82af4dd7"
            }
          ]
        }
      ]
    }
  ]
}
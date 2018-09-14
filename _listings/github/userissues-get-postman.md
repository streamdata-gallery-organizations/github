{
  "info": {
    "name": "Github Get User Issues",
    "_postman_id": "37cca77d-6a58-42ad-bf44-704bc863bf67",
    "description": "List issues.\nList all issues across owned and member repositories for the authenticated\nuser.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "user",
      "item": [
        {
          "id": "7fb6a049-b8b2-4c42-8da9-63506016c62b",
          "name": "list-issueslist-all-issues-across-owned-and-member-repositories-for-the-authenticateduser",
          "request": {
            "url": "http://api.github.com/user/issues?access_token=%7B%7D&direction=%7B%7D&filter=%7B%7D&labels=%7B%7D&since=%7B%7D&sort=%7B%7D&state=%7B%7D",
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
            "description": "List issues"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d12b732-62d4-41b5-8c8f-17c01a1d0e54"
            }
          ]
        }
      ]
    }
  ]
}
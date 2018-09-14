{
  "info": {
    "name": "Github Get User Teams",
    "_postman_id": "7306b561-a819-4c22-b411-19c0d3911c8a",
    "description": "List all of the teams across all of the organizations to which the authenticated user belongs. This method requires user or repo scope when authenticating via OAuth.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "user",
      "item": [
        {
          "id": "5595b41f-1ee6-4566-863a-61998fca2826",
          "name": "list-all-of-the-teams-across-all-of-the-organizations-to-which-the-authenticated-user-belongs-this-m",
          "request": {
            "url": "http://api.github.com/user/teams?access_token=%7B%7D",
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
            "description": "List all of the teams across all of the organizations to which the authenticated user belongs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "441a2029-e575-44ab-a54d-7870e7b67bcf"
            }
          ]
        }
      ]
    }
  ]
}
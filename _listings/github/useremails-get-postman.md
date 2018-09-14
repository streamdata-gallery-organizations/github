{
  "info": {
    "name": "Github Get User Emails",
    "_postman_id": "f0a62d9f-1eae-4a08-b322-fcaeb34e4084",
    "description": "List email addresses for a user.\nIn the final version of the API, this method will return an array of hashes\nwith extended information for each email address indicating if the address\nhas been verified and if it's primary email address for GitHub.\nUntil API v3 is finalized, use the application/vnd.github.v3 media type to\nget other response format.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "user",
      "item": [
        {
          "id": "e3d13741-7c02-4be9-a633-c940d0e0d83b",
          "name": "list-email-addresses-for-a-userin-the-final-version-of-the-api-this-method-will-return-an-array-of-h",
          "request": {
            "url": "http://api.github.com/user/emails?access_token=%7B%7D",
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
            "description": "List email addresses for a user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8914f9e2-2a9c-470c-b74b-02f8bcca9942"
            }
          ]
        }
      ]
    }
  ]
}
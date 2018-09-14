{
  "info": {
    "name": "Github Get User Repos",
    "_postman_id": "db09dbe4-0dea-4fb4-ace1-959b3186b6be",
    "description": "List repositories for the authenticated user. Note that this does not include\nrepositories owned by organizations which the user can access. You can lis\nuser organizations and list organization repositories separately.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "user",
      "item": [
        {
          "id": "76fffb3c-e0e4-4800-b5cd-a2a6ef489ac6",
          "name": "list-repositories-for-the-authenticated-user-note-that-this-does-not-includerepositories-owned-by-or",
          "request": {
            "url": "http://api.github.com/user/repos?access_token=%7B%7D&type=%7B%7D",
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
            "description": "List repositories for the authenticated user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74b8109a-3652-417d-bf22-9954d67561f7"
            }
          ]
        }
      ]
    }
  ]
}
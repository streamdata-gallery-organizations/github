{
  "info": {
    "name": "Github Get Issues",
    "_postman_id": "03588717-a36d-454b-ad72-d142c1795243",
    "description": "List issues.\nList all issues across all the authenticated user's visible repositories.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "issues",
      "item": [
        {
          "id": "4c297b49-554a-4322-b1bc-7630dcb023c4",
          "name": "list-issueslist-all-issues-across-all-the-authenticated-users-visible-repositories",
          "request": {
            "url": "http://api.github.com/issues?access_token=%7B%7D&direction=%7B%7D&filter=%7B%7D&labels=%7B%7D&since=%7B%7D&sort=%7B%7D&state=%7B%7D",
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
              "id": "aaa21e7e-649b-47b0-bd6c-912ea1163d24"
            }
          ]
        }
      ]
    }
  ]
}
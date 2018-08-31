{
  "info": {
    "name": "Github Get Notifications",
    "_postman_id": "f9a6bf3f-6fe6-4bc5-88aa-0ef660460fe3",
    "description": "List your notifications.\nList all notifications for the current user, grouped by repository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "notifications",
      "item": [
        {
          "id": "ed4e499c-42b7-4455-8e3c-dc4353bc4532",
          "name": "list-your-notificationslist-all-notifications-for-the-current-user-grouped-by-repository",
          "request": {
            "url": "http://api.github.com/notifications?access_token=%7B%7D&all=%7B%7D&participating=%7B%7D&since=%7B%7D",
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
            "description": "List your notifications"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa882d1c-3c42-4d8c-8856-52547d6c2e1e"
            }
          ]
        }
      ]
    }
  ]
}
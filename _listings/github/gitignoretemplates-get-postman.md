{
  "info": {
    "name": "Github Get Gitignore Templates",
    "_postman_id": "9b9560a4-24c1-4aee-8098-9a7fe6562193",
    "description": "Listing available templates.\nList all templates available to pass as an option when creating a repository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "gitignore",
      "item": [
        {
          "id": "a5714938-15ba-422c-82ee-6e99698fb462",
          "name": "listing-available-templateslist-all-templates-available-to-pass-as-an-option-when-creating-a-reposit",
          "request": {
            "url": "http://api.github.com/gitignore/templates?access_token=%7B%7D",
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
            "description": "Listing available templates"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0b1a2f6-f31a-490f-89bf-6517329c8ad2"
            }
          ]
        }
      ]
    }
  ]
}
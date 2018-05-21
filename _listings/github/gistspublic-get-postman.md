{
  "info": {
    "name": "Github Get Gists Public",
    "_postman_id": "59b725a4-529c-4410-bf68-d58b87e803a0",
    "description": "List all public gists.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Gists",
      "item": [
        {
          "id": "04bc143b-fc3f-4ed7-99c2-181fe2e65bda",
          "name": "list-all-public-gists",
          "request": {
            "url": "http://api.github.com/gists/public?access_token=%7B%7D&since=%7B%7D",
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
            "description": "List all public gists."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ed707312-dc46-4315-848e-f38a49d3c620"
            }
          ]
        }
      ]
    }
  ]
}
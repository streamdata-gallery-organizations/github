{
  "info": {
    "name": "Github Get Repositories",
    "_postman_id": "f67b580b-8a88-4447-8f6a-75116aea68d5",
    "description": "List all public repositories.\nThis provides a dump of every public repository, in the order that they\nwere created.\nNote: Pagination is powered exclusively by the since parameter. is the\nLink header to get the URL for the next page of repositories.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "3a4463bf-2ec1-47e7-8a4d-a36ead6bd98a",
          "name": "list-all-public-repositoriesthis-provides-a-dump-of-every-public-repository-in-the-order-that-theywe",
          "request": {
            "url": "http://api.github.com/repositories?access_token=%7B%7D&since=%7B%7D",
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
            "description": "List all public repositories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "407dba5d-db25-4391-b355-8cf33ca68532"
            }
          ]
        }
      ]
    }
  ]
}
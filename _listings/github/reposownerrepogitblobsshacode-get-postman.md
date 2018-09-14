{
  "info": {
    "name": "Github Get Repos Owner Repo Git Blobs Shacode",
    "_postman_id": "936e9543-2005-4dea-8020-964d0ad20ac5",
    "description": "Get a Blob.\nSince blobs can be any arbitrary binary data, the input and responses for\nthe blob API takes an encoding parameter that can be either utf-8 or\nbase64. If your data cannot be losslessly sent as a UTF-8 string, you can\nbase64 encode it.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "ef755f39-59a7-4e8a-9876-a11c54dbf8cf",
          "name": "get-a-blobsince-blobs-can-be-any-arbitrary-binary-data-the-input-and-responses-forthe-blob-api-takes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/git/blobs/:shaCode"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "owner",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "repo",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "shaCode",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Get a Blob"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3639965-70af-4dee-9cef-c9835e8b47e7"
            }
          ]
        }
      ]
    }
  ]
}
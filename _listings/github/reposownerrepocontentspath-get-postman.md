{
  "info": {
    "name": "Github Get Repos Owner Repo Contents Path",
    "_postman_id": "4a68e8e5-f4da-49d7-b2fc-fa8d609a310d",
    "description": "Get contents.\nThis method returns the contents of a file or directory in a repository.\nFiles and symlinks support a custom media type for getting the raw content.\nDirectories and submodules do not support custom media types.\nNote: This API supports files up to 1 megabyte in size.\nHere can be many outcomes. For details see \"http://developer.github.com/v3/repos/contents/\"",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "b2fa49aa-c751-483a-9830-aefed682cfde",
          "name": "get-contentsthis-method-returns-the-contents-of-a-file-or-directory-in-a-repositoryfiles-and-symlink",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/contents/:path"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ref",
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
                  "id": "path",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "repo",
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
            "description": "Get contents"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "536cca68-844b-4b86-b464-a9575bc4d0e7"
            }
          ]
        }
      ]
    }
  ]
}
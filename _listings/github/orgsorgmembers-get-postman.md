{
  "info": {
    "name": "Github Get Orgs Org Members",
    "_postman_id": "e9b09d49-3361-49ae-8ce8-1b339523b046",
    "description": "Members list.\nList all users who are members of an organization. A member is a user tha\nbelongs to at least 1 team in the organization. If the authenticated user\nis also an owner of this organization then both concealed and public members\nwill be returned. If the requester is not an owner of the organization the\nquery will be redirected to the public members list.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "orgs",
      "item": [
        {
          "id": "0a1973fd-05bf-4480-8ab7-f49122aecbf2",
          "name": "members-listlist-all-users-who-are-members-of-an-organization-a-member-is-a-user-thabelongs-to-at-le",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "orgs/:org/members"
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
                  "id": "org",
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
            "description": "Members list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3cd5385d-6c53-413e-95fe-120850eee1f7"
            }
          ]
        }
      ]
    }
  ]
}
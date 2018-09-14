---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Users Username Keys
  description: |-
    List public keys for a user.
    Lists the verified public keys for a user. This is accessible by anyone.
  termsOfService: https://help.github.com/articles/github-terms-of-service/#b-api-terms
  version: 1.0.0
host: api.github.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{username}/keys:
    get:
      summary: Get Users Username Keys
      description: |-
        List public keys for a user.
        Lists the verified public keys for a user. This is accessible by anyone.
      operationId: list-public-keys-for-a-userlists-the-verified-public-keys-for-a-user-this-is-accessible-by-anyone
      x-api-path-slug: usersusernamekeys-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: username
        description: Name of user
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Keys
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
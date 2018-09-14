---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Users Username Following Targetuser
  description: Check if one user follows another.
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
  /users/{username}/following/{targetUser}:
    get:
      summary: Get Users Username Following Targetuser
      description: Check if one user follows another.
      operationId: check-if-one-user-follows-another
      x-api-path-slug: usersusernamefollowingtargetuser-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: targetUser
        description: Name of user
      - in: path
        name: username
        description: Name of user
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Following
      - Targetuser
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
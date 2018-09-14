---
paths:
  /users/{username}/repos:
    get:
      summary: Get Users Username Repos
      description: List public repositories for the specified user.
      operationId: list-public-repositories-for-the-specified-user
      x-api-path-slug: usersusernamerepos-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: type
      - in: path
        name: username
        description: Name of user
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Repos
x-complete: 0
info:
  title: Github Get Users Username Repos
  description: List public repositories for the specified user.
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
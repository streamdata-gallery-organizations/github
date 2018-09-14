---
paths:
  /users/{username}/starred:
    get:
      summary: Get Users Username Starred
      description: List repositories being starred by a user.
      operationId: list-repositories-being-starred-by-a-user
      x-api-path-slug: usersusernamestarred-get
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
      - Starred
x-complete: 0
info:
  title: Github Get Users Username Starred
  description: List repositories being starred by a user.
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
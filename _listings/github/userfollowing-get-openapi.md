---
paths:
  /user/following:
    get:
      summary: Get User Following
      description: List who the authenticated user is following.
      operationId: list-who-the-authenticated-user-is-following
      x-api-path-slug: userfollowing-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      responses:
        200:
          description: OK
      tags:
      - User
      - Following
x-complete: 0
info:
  title: Github Get User Following
  description: List who the authenticated user is following.
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
---
paths:
  /user/starred:
    get:
      summary: Get User Starred
      description: List repositories being starred by the authenticated user.
      operationId: list-repositories-being-starred-by-the-authenticated-user
      x-api-path-slug: userstarred-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
        description: Ignored without sort parameter
      - in: query
        name: sort
      responses:
        200:
          description: OK
      tags:
      - User
      - Starred
x-complete: 0
info:
  title: Github Get User Starred
  description: List repositories being starred by the authenticated user.
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
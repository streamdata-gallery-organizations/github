---
paths:
  /user/followers:
    get:
      summary: Get User Followers
      description: List the authenticated user's followers
      operationId: list-the-authenticated-users-followers
      x-api-path-slug: userfollowers-get
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
      - Followers
x-complete: 0
info:
  title: Github Get User Followers
  description: List the authenticated user's followers
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
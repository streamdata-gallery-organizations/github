---
paths:
  /user/following/{username}:
    put:
      summary: Put User Following Username
      description: |-
        Follow a user.
        Following a user requires the user to be logged in and authenticated with
        basic auth or OAuth with the user:follow scope.
      operationId: follow-a-userfollowing-a-user-requires-the-user-to-be-logged-in-and-authenticated-withbasic-auth-or-
      x-api-path-slug: userfollowingusername-put
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
      - User
      - Following
      - Username
x-complete: 0
info:
  title: Github Put User Following Username
  description: |-
    Follow a user.
    Following a user requires the user to be logged in and authenticated with
    basic auth or OAuth with the user:follow scope.
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
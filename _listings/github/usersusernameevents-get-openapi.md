---
paths:
  /users/{username}/events:
    get:
      summary: Get Users Username Events
      description: If you are authenticated as the given user, you will see your private
        events. Otherwise, you'll only see public events.
      operationId: if-you-are-authenticated-as-the-given-user-you-will-see-your-private-events-otherwise-youll-only-see
      x-api-path-slug: usersusernameevents-get
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
      - Events
x-complete: 0
info:
  title: Github Get Users Username Events
  description: If you are authenticated as the given user, you will see your private
    events. Otherwise, you'll only see public events.
x-streamrank:
  polling_total_time_average: "0.21"
  polling_size_download_average: "31132.75"
  streaming_total_time_average: "0.12"
  streaming_size_download_average: "15579.5"
  change_yes: "111"
  change_no: "2223"
  time_percentage: "44"
  size_percentage: "50"
  change_percentage: "5"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
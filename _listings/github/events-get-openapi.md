---
paths:
  /events:
    get:
      summary: Get Events
      description: List public events.
      operationId: list-public-events
      x-api-path-slug: events-get
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
      - Events
x-complete: 0
info:
  title: Github Get Events
  description: List public events.
x-streamrank:
  polling_total_time_average: "0.27"
  polling_size_download_average: "79984.96"
  streaming_total_time_average: "0.15"
  streaming_size_download_average: "44088.69"
  change_yes: "2340"
  change_no: "1"
  time_percentage: "45"
  size_percentage: "45"
  change_percentage: "100"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
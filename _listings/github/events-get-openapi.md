---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Events
  description: List public events.
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
  /emojis:
    get:
      summary: Get Emojis
      description: Lists all the emojis available to use on GitHub.
      operationId: lists-all-the-emojis-available-to-use-on-github
      x-api-path-slug: emojis-get
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
      - Emojis
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
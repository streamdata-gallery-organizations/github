---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Emojis
  description: Lists all the emojis available to use on GitHub.
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
x-streamrank:
  polling_total_time_average: "0.12"
  polling_size_download_average: "129852.21"
  streaming_total_time_average: "0.07"
  streaming_size_download_average: "64953.89"
  change_yes: "5"
  change_no: "2340"
  time_percentage: "38"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Gists Public
  description: List all public gists.
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
  /gists/public:
    get:
      summary: Get Gists Public
      description: List all public gists.
      operationId: list-all-public-gists
      x-api-path-slug: gistspublic-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: since
        description: Timestamp in ISO 8601 format YYYY-MM-DDTHH:MM:SSZ
      responses:
        200:
          description: OK
      tags:
      - Gists
      - Public
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
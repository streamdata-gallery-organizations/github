---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Gists
  description: |-
    List the authenticated user's gists or if called anonymously, this will
    return all public gists.
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
  /gists:
    get:
      summary: Get Gists
      description: |-
        List the authenticated user's gists or if called anonymously, this will
        return all public gists.
      operationId: list-the-authenticated-users-gists-or-if-called-anonymously-this-willreturn-all-public-gists
      x-api-path-slug: gists-get
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
x-streamrank:
  polling_total_time_average: "0.44"
  polling_size_download_average: "57617.31"
  streaming_total_time_average: "0.23"
  streaming_size_download_average: "28833.23"
  change_yes: "14"
  change_no: "2330"
  time_percentage: "47"
  size_percentage: "50"
  change_percentage: "1"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
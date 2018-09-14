---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Rate Limit
  description: |-
    Get your current rate limit status
    Note: Accessing this endpoint does not count against your rate limit.
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
  /rate_limit:
    get:
      summary: Get Rate Limit
      description: |-
        Get your current rate limit status
        Note: Accessing this endpoint does not count against your rate limit.
      operationId: get-your-current-rate-limit-statusnote-accessing-this-endpoint-does-not-count-against-your-rate-limi
      x-api-path-slug: rate-limit-get
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
      - Rate
      - Limit
x-streamrank:
  polling_total_time_average: "0.1"
  polling_size_download_average: "247.97"
  streaming_total_time_average: "0.06"
  streaming_size_download_average: "123.99"
  change_yes: "76"
  change_no: "2258"
  time_percentage: "38"
  size_percentage: "50"
  change_percentage: "3"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
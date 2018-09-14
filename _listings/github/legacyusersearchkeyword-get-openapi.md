---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Legacy User Search Keyword
  description: Find users by keyword.
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
  /legacy/user/search/{keyword}:
    get:
      summary: Get Legacy User Search Keyword
      description: Find users by keyword.
      operationId: find-users-by-keyword
      x-api-path-slug: legacyusersearchkeyword-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: keyword
        description: The search term
      - in: query
        name: order
        description: The sort field
      - in: query
        name: sort
        description: The sort field
      - in: query
        name: start_page
        description: The page number to fetch
      responses:
        200:
          description: OK
      tags:
      - Legacy
      - User
      - Search
      - Keyword
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
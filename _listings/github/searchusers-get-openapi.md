---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Search Users
  description: Search users.
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
  /search/users:
    get:
      summary: Get Search Users
      description: Search users.
      operationId: search-users
      x-api-path-slug: searchusers-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: order
        description: The sort field
      - in: query
        name: q
        description: The search terms
      - in: query
        name: sort
        description: If not provided, results are sorted by best match
      responses:
        200:
          description: OK
      tags:
      - Search
      - Users
x-streamrank:
  polling_total_time_average: "0.18"
  polling_size_download_average: "26688.22"
  streaming_total_time_average: "0.1"
  streaming_size_download_average: "13344.47"
  change_yes: "2150"
  change_no: "185"
  time_percentage: "43"
  size_percentage: "50"
  change_percentage: "92"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
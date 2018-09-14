---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Search Repositories
  description: Search repositories.
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
  /search/repositories:
    get:
      summary: Get Search Repositories
      description: Search repositories.
      operationId: search-repositories
      x-api-path-slug: searchrepositories-get
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
      - Repositories
x-streamrank:
  polling_total_time_average: "0.7"
  polling_size_download_average: "149672.32"
  streaming_total_time_average: "0.36"
  streaming_size_download_average: "74868.58"
  change_yes: "2130"
  change_no: "205"
  time_percentage: "48"
  size_percentage: "50"
  change_percentage: "91"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Orgs Org
  description: Get an Organization.
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
  /orgs/{org}:
    get:
      summary: Get Orgs Org
      description: Get an Organization.
      operationId: get-an-organization
      x-api-path-slug: orgsorg-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of organisation
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
x-streamrank:
  polling_total_time_average: "0.14"
  polling_size_download_average: "1397.69"
  streaming_total_time_average: "0.08"
  streaming_size_download_average: "699.15"
  change_yes: "4"
  change_no: "2339"
  time_percentage: "42"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
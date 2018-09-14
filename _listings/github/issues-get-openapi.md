---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Issues
  description: |-
    List issues.
    List all issues across all the authenticated user's visible repositories.
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
  /issues:
    get:
      summary: Get Issues
      description: |-
        List issues.
        List all issues across all the authenticated user's visible repositories.
      operationId: list-issueslist-all-issues-across-all-the-authenticated-users-visible-repositories
      x-api-path-slug: issues-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
      - in: query
        name: filter
        description: Issues assigned to you / created by you / mentioning you / youresubscribed
          to updates for / All issues the authenticated user can see
      - in: query
        name: labels
        description: String list of comma separated Label names
      - in: query
        name: since
        description: 'Optional string of a timestamp in ISO 8601 format: YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: sort
      - in: query
        name: state
      responses:
        200:
          description: OK
      tags:
      - Issues
x-streamrank:
  polling_total_time_average: "0.31"
  polling_size_download_average: "57398.7"
  streaming_total_time_average: "0.17"
  streaming_size_download_average: "28699.35"
  change_yes: "5"
  change_no: "2336"
  time_percentage: "46"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
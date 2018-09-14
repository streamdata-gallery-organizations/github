---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Repos Owner Repo Issues
  description: List issues for a repository.
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
  /repos/{owner}/{repo}/issues:
    get:
      summary: Get Repos Owner Repo Issues
      description: List issues for a repository.
      operationId: list-issues-for-a-repository
      x-api-path-slug: reposownerrepoissues-get
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
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
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
      - Repos
      - Owner
      - Repo
      - Issues
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
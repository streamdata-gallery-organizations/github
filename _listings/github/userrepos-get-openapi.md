---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get User Repos
  description: |-
    List repositories for the authenticated user. Note that this does not include
    repositories owned by organizations which the user can access. You can lis
    user organizations and list organization repositories separately.
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
  /user/repos:
    get:
      summary: Get User Repos
      description: |-
        List repositories for the authenticated user. Note that this does not include
        repositories owned by organizations which the user can access. You can lis
        user organizations and list organization repositories separately.
      operationId: list-repositories-for-the-authenticated-user-note-that-this-does-not-includerepositories-owned-by-or
      x-api-path-slug: userrepos-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - User
      - Repos
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
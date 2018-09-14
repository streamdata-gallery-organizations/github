---
paths:
  /user/repos:
    post:
      summary: Add User Repos
      description: |-
        Create a new repository for the authenticated user. OAuth users must supply
        repo scope.
      operationId: create-a-new-repository-for-the-authenticated-user-oauth-users-must-supplyrepo-scope
      x-api-path-slug: userrepos-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - User
      - Repos
x-complete: 0
info:
  title: Github Add User Repos
  description: |-
    Create a new repository for the authenticated user. OAuth users must supply
    repo scope.
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
---
paths:
  /gists/{id}/comments:
    post:
      summary: Add Gists  Comments
      description: Create a commen
      operationId: create-a-commen
      x-api-path-slug: gistsidcomments-post
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
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
x-complete: 0
info:
  title: Github Add Gists  Comments
  description: Create a commen
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
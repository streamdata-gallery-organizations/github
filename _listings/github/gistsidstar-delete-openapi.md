---
paths:
  /gists/{id}/star:
    delete:
      summary: Delete Gists  Star
      description: Unstar a gist.
      operationId: unstar-a-gist
      x-api-path-slug: gistsidstar-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Star
x-complete: 0
info:
  title: Github Delete Gists  Star
  description: Unstar a gist.
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
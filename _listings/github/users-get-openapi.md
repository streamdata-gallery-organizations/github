---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Users
  description: |-
    Get all users.
    This provides a dump of every user, in the order that they signed up for GitHub.
    Note: Pagination is powered exclusively by the since parameter. Use the Link
    header to get the URL for the next page of users.
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
  /users:
    get:
      summary: Get Users
      description: |-
        Get all users.
        This provides a dump of every user, in the order that they signed up for GitHub.
        Note: Pagination is powered exclusively by the since parameter. Use the Link
        header to get the URL for the next page of users.
      operationId: get-all-usersthis-provides-a-dump-of-every-user-in-the-order-that-they-signed-up-for-githubnote-pagi
      x-api-path-slug: users-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: since
        description: The integer ID of the last User that youve seen
      responses:
        200:
          description: OK
      tags:
      - Users
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
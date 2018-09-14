---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Legacy User Email Email
  description: This API call is added for compatibility reasons only.
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
  /legacy/user/email/{email}:
    get:
      summary: Get Legacy User Email Email
      description: This API call is added for compatibility reasons only.
      operationId: this-api-call-is-added-for-compatibility-reasons-only
      x-api-path-slug: legacyuseremailemail-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: email
        description: The email address
      responses:
        200:
          description: OK
      tags:
      - Legacy
      - User
      - Email
      - Email
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
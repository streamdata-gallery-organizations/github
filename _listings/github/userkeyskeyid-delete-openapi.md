---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Delete User Keys Key
  description: Delete a public key. Removes a public key. Requires that you are authenticated
    via Basic Auth or via OAuth with at least admin:public_key scope.
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
  /user/keys/{keyId}:
    delete:
      summary: Delete User Keys Key
      description: Delete a public key. Removes a public key. Requires that you are
        authenticated via Basic Auth or via OAuth with at least admin:public_key scope.
      operationId: delete-a-public-key-removes-a-public-key-requires-that-you-are-authenticated-via-basic-auth-or-via-o
      x-api-path-slug: userkeyskeyid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: keyId
        description: ID of key
      responses:
        200:
          description: OK
      tags:
      - User
      - Keys
      - Key
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
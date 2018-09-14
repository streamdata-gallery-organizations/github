---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get User Keys
  description: |-
    List your public keys.
    Lists the current user's keys. Management of public keys via the API requires
    that you are authenticated through basic auth, or OAuth with the 'user', 'write:public_key' scopes.
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
  /user/keys:
    get:
      summary: Get User Keys
      description: |-
        List your public keys.
        Lists the current user's keys. Management of public keys via the API requires
        that you are authenticated through basic auth, or OAuth with the 'user', 'write:public_key' scopes.
      operationId: list-your-public-keyslists-the-current-users-keys-management-of-public-keys-via-the-api-requiresthat
      x-api-path-slug: userkeys-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      responses:
        200:
          description: OK
      tags:
      - User
      - Keys
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
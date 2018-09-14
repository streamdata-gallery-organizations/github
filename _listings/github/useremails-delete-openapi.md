---
paths:
  /user/emails:
    delete:
      summary: Delete User Emails
      description: |-
        Delete email address(es).
        You can include a single email address or an array of addresses.
      operationId: delete-email-addressesyou-can-include-a-single-email-address-or-an-array-of-addresses
      x-api-path-slug: useremails-delete
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
      - Emails
x-complete: 0
info:
  title: Github Delete User Emails
  description: |-
    Delete email address(es).
    You can include a single email address or an array of addresses.
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
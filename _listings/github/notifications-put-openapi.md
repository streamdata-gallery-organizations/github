---
paths:
  /notifications:
    put:
      summary: Put Notifications
      description: |-
        Mark as read.
        Marking a notification as "read" removes it from the default view on GitHub.com.
      operationId: mark-as-readmarking-a-notification-as-read-removes-it-from-the-default-view-on-githubcom
      x-api-path-slug: notifications-put
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
      - Notifications
x-complete: 0
info:
  title: Github Put Notifications
  description: |-
    Mark as read.
    Marking a notification as "read" removes it from the default view on GitHub.com.
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
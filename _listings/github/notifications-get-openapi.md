---
paths:
  /notifications:
    get:
      summary: Get Notifications
      description: |-
        List your notifications.
        List all notifications for the current user, grouped by repository.
      operationId: list-your-notificationslist-all-notifications-for-the-current-user-grouped-by-repository
      x-api-path-slug: notifications-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: all
        description: True to show notifications marked as read
      - in: query
        name: participating
        description: True to show only notifications in which the user is directly
          participatingor mentioned
      - in: query
        name: since
        description: 'The time should be passed in as UTC in the ISO 8601 format:
          YYYY-MM-DDTHH:MM:SSZ'
      responses:
        200:
          description: OK
      tags:
      - Notifications
x-complete: 0
info:
  title: Github Get Notifications
  description: |-
    List your notifications.
    List all notifications for the current user, grouped by repository.
x-streamrank:
  polling_total_time_average: "0.12"
  polling_size_download_average: "25718.36"
  streaming_total_time_average: "0.07"
  streaming_size_download_average: "12860.26"
  change_yes: "13"
  change_no: "2328"
  time_percentage: "39"
  size_percentage: "50"
  change_percentage: "1"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
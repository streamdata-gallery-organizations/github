---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Repos Owner Repo Notifications
  description: |-
    List your notifications in a repository
    List all notifications for the current user.
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
  /repos/{owner}/{repo}/notifications:
    get:
      summary: Get Repos Owner Repo Notifications
      description: |-
        List your notifications in a repository
        List all notifications for the current user.
      operationId: list-your-notifications-in-a-repositorylist-all-notifications-for-the-current-user
      x-api-path-slug: reposownerreponotifications-get
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
      - in: path
        name: owner
        description: Name of repository owner
      - in: query
        name: participating
        description: True to show only notifications in which the user is directly
          participatingor mentioned
      - in: path
        name: repo
        description: Name of repository
      - in: query
        name: since
        description: 'The time should be passed in as UTC in the ISO 8601 format:
          YYYY-MM-DDTHH:MM:SSZ'
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Notifications
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
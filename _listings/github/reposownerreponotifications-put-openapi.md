---
paths:
  /repos/{owner}/{repo}/notifications:
    put:
      summary: Put Repos Owner Repo Notifications
      description: |-
        Mark notifications as read in a repository.
        Marking all notifications in a repository as "read" removes them from the
        default view on GitHub.com.
      operationId: mark-notifications-as-read-in-a-repositorymarking-all-notifications-in-a-repository-as-read-removes-
      x-api-path-slug: reposownerreponotifications-put
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
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Notifications
x-complete: 0
info:
  title: Github Put Repos Owner Repo Notifications
  description: |-
    Mark notifications as read in a repository.
    Marking all notifications in a repository as "read" removes them from the
    default view on GitHub.com.
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
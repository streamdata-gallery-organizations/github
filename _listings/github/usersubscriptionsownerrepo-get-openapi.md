---
paths:
  /user/subscriptions/{owner}/{repo}:
    get:
      summary: Get User Subscriptions Owner Repo
      description: Check if you are watching a repository.
      operationId: check-if-you-are-watching-a-repository
      x-api-path-slug: usersubscriptionsownerrepo-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of the owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - User
      - Subscriptions
      - Owner
      - Repo
x-complete: 0
info:
  title: Github Get User Subscriptions Owner Repo
  description: Check if you are watching a repository.
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
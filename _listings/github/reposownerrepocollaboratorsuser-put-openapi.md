---
paths:
  /repos/{owner}/{repo}/collaborators/{user}:
    put:
      summary: Put Repos Owner Repo Collaborators User
      description: Add collaborator.
      operationId: add-collaborator
      x-api-path-slug: reposownerrepocollaboratorsuser-put
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: user
        description: Login of the user
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Collaborators
      - User
x-complete: 0
info:
  title: Github Put Repos Owner Repo Collaborators User
  description: Add collaborator.
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
---
paths:
  /repos/{owner}/{repo}/assignees/{assignee}:
    get:
      summary: Get Repos Owner Repo Assignees Assignee
      description: |-
        Check assignee.
        You may also check to see if a particular user is an assignee for a repository.
      operationId: check-assigneeyou-may-also-check-to-see-if-a-particular-user-is-an-assignee-for-a-repository
      x-api-path-slug: reposownerrepoassigneesassignee-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: assignee
        description: Login of the assignee
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
      - Assignees
      - Assignee
x-complete: 0
info:
  title: Github Get Repos Owner Repo Assignees Assignee
  description: |-
    Check assignee.
    You may also check to see if a particular user is an assignee for a repository.
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
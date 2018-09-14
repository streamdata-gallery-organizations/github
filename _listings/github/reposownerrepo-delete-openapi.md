---
paths:
  /repos/{owner}/{repo}:
    delete:
      summary: Delete Repos Owner Repo
      description: |-
        Delete a Repository.
        Deleting a repository requires admin access. If OAuth is used, the delete_repo
        scope is required.
      operationId: delete-a-repositorydeleting-a-repository-requires-admin-access-if-oauth-is-used-the-delete-reposcope
      x-api-path-slug: reposownerrepo-delete
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
x-complete: 0
info:
  title: Github Delete Repos Owner Repo
  description: |-
    Delete a Repository.
    Deleting a repository requires admin access. If OAuth is used, the delete_repo
    scope is required.
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
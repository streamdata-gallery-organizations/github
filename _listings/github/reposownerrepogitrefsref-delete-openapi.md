---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Delete Repos Owner Repo Git Refs Ref
  description: "Delete a Reference\nExample: Deleting a branch: DELETE /repos/octocat/Hello-World/git/refs/heads/feature-a
    \nExample: Deleting a tag:        DELETE /repos/octocat/Hello-World/git/refs/tags/v1.0"
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
  /repos/{owner}/{repo}/git/refs/{ref}:
    delete:
      summary: Delete Repos Owner Repo Git Refs Ref
      description: "Delete a Reference\nExample: Deleting a branch: DELETE /repos/octocat/Hello-World/git/refs/heads/feature-a
        \nExample: Deleting a tag:        DELETE /repos/octocat/Hello-World/git/refs/tags/v1.0"
      operationId: delete-a-referenceexample-deleting-a-branch-delete-reposoctocathelloworldgitrefsheadsfeaturea-exampl
      x-api-path-slug: reposownerrepogitrefsref-delete
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
        name: ref
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
      - Git
      - Refs
      - Ref
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
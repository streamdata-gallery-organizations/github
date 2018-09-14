---
paths:
  /repos/{owner}/{repo}/releases/{id}:
    delete:
      summary: Delete Repos Owner Repo Releases
      description: Users with push access to the repository can delete a release.
      operationId: users-with-push-access-to-the-repository-can-delete-a-release
      x-api-path-slug: reposownerreporeleasesid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
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
      - Releases
x-complete: 0
info:
  title: Github Delete Repos Owner Repo Releases
  description: Users with push access to the repository can delete a release.
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
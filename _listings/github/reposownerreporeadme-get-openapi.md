---
paths:
  /repos/{owner}/{repo}/readme:
    get:
      summary: Get Repos Owner Repo Readme
      description: |-
        Get the README.
        This method returns the preferred README for a repository.
      operationId: get-the-readmethis-method-returns-the-preferred-readme-for-a-repository
      x-api-path-slug: reposownerreporeadme-get
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
      - in: query
        name: ref
        description: The String name of the Commit/Branch/Tag
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
      - Readme
x-complete: 0
info:
  title: Github Get Repos Owner Repo Readme
  description: |-
    Get the README.
    This method returns the preferred README for a repository.
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
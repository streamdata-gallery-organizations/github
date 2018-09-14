---
paths:
  /repos/{owner}/{repo}/downloads/{downloadId}:
    get:
      summary: Get Repos Owner Repo Downloads Download
      description: Deprecated. Get a single download.
      operationId: deprecated-get-a-single-download
      x-api-path-slug: reposownerrepodownloadsdownloadid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: downloadId
        description: Id of download
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
      - Downloads
      - Download
x-complete: 0
info:
  title: Github Get Repos Owner Repo Downloads Download
  description: Deprecated. Get a single download.
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
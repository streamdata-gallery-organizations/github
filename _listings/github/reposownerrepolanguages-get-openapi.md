---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Repos Owner Repo Languages
  description: |-
    List languages.
    List languages for the specified repository. The value on the right of a
    language is the number of bytes of code written in that language.
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
  /repos/{owner}/{repo}/languages:
    get:
      summary: Get Repos Owner Repo Languages
      description: |-
        List languages.
        List languages for the specified repository. The value on the right of a
        language is the number of bytes of code written in that language.
      operationId: list-languageslist-languages-for-the-specified-repository-the-value-on-the-right-of-alanguage-is-the
      x-api-path-slug: reposownerrepolanguages-get
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
      - Languages
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
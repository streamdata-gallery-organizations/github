---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Repos Owner Repo Commits
  description: List commits on a repository.
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
  /repos/{owner}/{repo}/commits:
    get:
      summary: Get Repos Owner Repo Commits
      description: List commits on a repository.
      operationId: list-commits-on-a-repository
      x-api-path-slug: reposownerrepocommits-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: author
        description: GitHub login, name, or email by which to filter by commit author
      - in: path
        name: owner
        description: Name of repository owner
      - in: query
        name: path
        description: Only commits containing this file path will be returned
      - in: path
        name: repo
        description: Name of repository
      - in: query
        name: sha
        description: Sha or branch to start listing commits from
      - in: query
        name: since
        description: 'The time should be passed in as UTC in the ISO 8601 format:
          YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: until
        description: ISO 8601 Date - Only commits before this date will be returned
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
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
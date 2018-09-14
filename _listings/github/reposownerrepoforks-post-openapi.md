---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Add Repos Owner Repo Forks
  description: |-
    Create a fork.
    Forking a Repository happens asynchronously. Therefore, you may have to wai
    a short period before accessing the git objects. If this takes longer than 5
    minutes, be sure to contact Support.
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
  /repos/{owner}/{repo}/forks:
    post:
      summary: Add Repos Owner Repo Forks
      description: |-
        Create a fork.
        Forking a Repository happens asynchronously. Therefore, you may have to wai
        a short period before accessing the git objects. If this takes longer than 5
        minutes, be sure to contact Support.
      operationId: create-a-forkforking-a-repository-happens-asynchronously-therefore-you-may-have-to-waia-short-period
      x-api-path-slug: reposownerrepoforks-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
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
      - Forks
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
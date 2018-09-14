---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Add Repos Owner Repo Git Trees
  description: |-
    Create a Tree.
    The tree creation API will take nested entries as well. If both a tree and
    a nested path modifying that tree are specified, it will overwrite the
    contents of that tree with the new path contents and write a new tree out.
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
  /repos/{owner}/{repo}/git/trees:
    post:
      summary: Add Repos Owner Repo Git Trees
      description: |-
        Create a Tree.
        The tree creation API will take nested entries as well. If both a tree and
        a nested path modifying that tree are specified, it will overwrite the
        contents of that tree with the new path contents and write a new tree out.
      operationId: create-a-treethe-tree-creation-api-will-take-nested-entries-as-well-if-both-a-tree-anda-nested-path-
      x-api-path-slug: reposownerrepogittrees-post
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
      - Git
      - Trees
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
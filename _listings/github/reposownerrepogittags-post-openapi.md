---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Add Repos Owner Repo Git Tags
  description: |-
    Create a Tag Object.
    Note that creating a tag object does not create the reference that makes a
    tag in Git. If you want to create an annotated tag in Git, you have to do
    this call to create the tag object, and then create the refs/tags/[tag]
    reference. If you want to create a lightweight tag, you only have to create
    the tag reference - this call would be unnecessary.
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
  /repos/{owner}/{repo}/git/tags:
    post:
      summary: Add Repos Owner Repo Git Tags
      description: |-
        Create a Tag Object.
        Note that creating a tag object does not create the reference that makes a
        tag in Git. If you want to create an annotated tag in Git, you have to do
        this call to create the tag object, and then create the refs/tags/[tag]
        reference. If you want to create a lightweight tag, you only have to create
        the tag reference - this call would be unnecessary.
      operationId: create-a-tag-objectnote-that-creating-a-tag-object-does-not-create-the-reference-that-makes-atag-in-
      x-api-path-slug: reposownerrepogittags-post
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
      - Tags
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
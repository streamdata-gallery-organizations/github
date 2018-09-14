---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Delete Orgs Org Members Username
  description: |-
    Remove a member.
    Removing a user from this list will remove them from all teams and they
    will no longer have any access to the organization's repositories.
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
  /orgs/{org}/members/{username}:
    delete:
      summary: Delete Orgs Org Members Username
      description: |-
        Remove a member.
        Removing a user from this list will remove them from all teams and they
        will no longer have any access to the organization's repositories.
      operationId: remove-a-memberremoving-a-user-from-this-list-will-remove-them-from-all-teams-and-theywill-no-longer
      x-api-path-slug: orgsorgmembersusername-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of organisation
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Members
      - Username
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
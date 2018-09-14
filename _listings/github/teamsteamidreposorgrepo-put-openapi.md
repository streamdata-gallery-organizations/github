---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Put Teams Team Repos Org Repo
  description: In order to add a repository to a team, the authenticated user must
    be an owner of the org that the team is associated with. Also, the repository
    must be owned by the organization, or a direct fork of a repository owned by the
    organization.
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
  /teams/{teamId}/repos/{org}/{repo}:
    put:
      summary: Put Teams Team Repos Org Repo
      description: In order to add a repository to a team, the authenticated user
        must be an owner of the org that the team is associated with. Also, the repository
        must be owned by the organization, or a direct fork of a repository owned
        by the organization.
      operationId: in-order-to-add-a-repository-to-a-team-the-authenticated-user-must-be-an-owner-of-the-org-that-the-t
      x-api-path-slug: teamsteamidreposorgrepo-put
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of a organization
      - in: path
        name: repo
        description: Name of a repository
      - in: path
        name: teamId
        description: Id of team
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
      - Repos
      - Org
      - Repo
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
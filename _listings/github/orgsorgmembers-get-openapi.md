---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Orgs Org Members
  description: |-
    Members list.
    List all users who are members of an organization. A member is a user tha
    belongs to at least 1 team in the organization. If the authenticated user
    is also an owner of this organization then both concealed and public members
    will be returned. If the requester is not an owner of the organization the
    query will be redirected to the public members list.
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
  /orgs/{org}/members:
    get:
      summary: Get Orgs Org Members
      description: |-
        Members list.
        List all users who are members of an organization. A member is a user tha
        belongs to at least 1 team in the organization. If the authenticated user
        is also an owner of this organization then both concealed and public members
        will be returned. If the requester is not an owner of the organization the
        query will be redirected to the public members list.
      operationId: members-listlist-all-users-who-are-members-of-an-organization-a-member-is-a-user-thabelongs-to-at-le
      x-api-path-slug: orgsorgmembers-get
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
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Members
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
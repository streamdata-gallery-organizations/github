---
paths:
  /orgs/{org}/public_members/{username}:
    put:
      summary: Put Orgs Org Public Members Username
      description: Publicize a user's membership.
      operationId: publicize-a-users-membership
      x-api-path-slug: orgsorgpublic-membersusername-put
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
      - Public
      - Members
      - Username
x-complete: 0
info:
  title: Github Put Orgs Org Public Members Username
  description: Publicize a user's membership.
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
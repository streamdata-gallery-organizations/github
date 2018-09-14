---
paths:
  /teams/{teamId}:
    patch:
      summary: Patch Teams Team
      description: |-
        Edit team.
        In order to edit a team, the authenticated user must be an owner of the org
        that the team is associated with.
      operationId: edit-teamin-order-to-edit-a-team-the-authenticated-user-must-be-an-owner-of-the-orgthat-the-team-is-
      x-api-path-slug: teamsteamid-patch
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
        name: teamId
        description: Id of team
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
x-complete: 0
info:
  title: Github Patch Teams Team
  description: |-
    Edit team.
    In order to edit a team, the authenticated user must be an owner of the org
    that the team is associated with.
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
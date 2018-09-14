---
paths:
  /teams/{teamId}/memberships/{username}:
    get:
      summary: Get Teams Team Memberships Username
      description: |-
        Get team membership.
        In order to get a user's membership with a team, the authenticated user must be a member of the team or an owner of the team's organization.
      operationId: get-team-membershipin-order-to-get-a-users-membership-with-a-team-the-authenticated-user-must-be-a-m
      x-api-path-slug: teamsteamidmembershipsusername-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: teamId
        description: Id of team
      - in: path
        name: username
        description: Name of a member
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
      - Memberships
      - Username
x-complete: 0
info:
  title: Github Get Teams Team Memberships Username
  description: |-
    Get team membership.
    In order to get a user's membership with a team, the authenticated user must be a member of the team or an owner of the team's organization.
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
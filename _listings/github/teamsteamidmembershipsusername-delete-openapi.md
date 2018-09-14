---
paths:
  /teams/{teamId}/memberships/{username}:
    delete:
      summary: Delete Teams Team Memberships Username
      description: |-
        Remove team membership.
        In order to remove a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with. NOTE: This does not delete the user, it just removes their membership from the team.
      operationId: remove-team-membershipin-order-to-remove-a-membership-between-a-user-and-a-team-the-authenticated-us
      x-api-path-slug: teamsteamidmembershipsusername-delete
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
  title: Github Delete Teams Team Memberships Username
  description: |-
    Remove team membership.
    In order to remove a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with. NOTE: This does not delete the user, it just removes their membership from the team.
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
---
paths:
  /teams/{teamId}/members/{username}:
    get:
      summary: Get Teams Team Members Username
      description: |-
        The "Get team member" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Get team membership API instead. It allows you to get both active and pending memberships.

        Get team member.
        In order to get if a user is a member of a team, the authenticated user mus
        be a member of the team.
      operationId: the-get-team-member-api-is-deprecated-and-is-scheduled-for-removal-in-the-next-major-version-of-the-
      x-api-path-slug: teamsteamidmembersusername-get
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
      - Members
      - Username
x-complete: 0
info:
  title: Github Get Teams Team Members Username
  description: |-
    The "Get team member" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Get team membership API instead. It allows you to get both active and pending memberships.

    Get team member.
    In order to get if a user is a member of a team, the authenticated user mus
    be a member of the team.
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
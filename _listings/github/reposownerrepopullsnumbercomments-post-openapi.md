---
paths:
  /repos/{owner}/{repo}/pulls/{number}/comments:
    post:
      summary: Add Repos Owner Repo Pulls Number Comments
      description: |-
        Create a comment.
          #TODO Alternative input ( http://developer.github.com/v3/pulls/comments/ )
          description: |
            Alternative Input.
            Instead of passing commit_id, path, and position you can reply to an
            existing Pull Request Comment like this:

                body
                   Required string
                in_reply_to
                   Required number - Comment id to reply to.
      operationId: create-a-comment--todo-alternative-input--httpdevelopergithubcomv3pullscomments---description-----al
      x-api-path-slug: reposownerrepopullsnumbercomments-post
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
        name: number
        description: Id of pull
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
      - Pulls
      - Number
      - Comments
x-complete: 0
info:
  title: Github Add Repos Owner Repo Pulls Number Comments
  description: |-
    Create a comment.
      #TODO Alternative input ( http://developer.github.com/v3/pulls/comments/ )
      description: |
        Alternative Input.
        Instead of passing commit_id, path, and position you can reply to an
        existing Pull Request Comment like this:

            body
               Required string
            in_reply_to
               Required number - Comment id to reply to.
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
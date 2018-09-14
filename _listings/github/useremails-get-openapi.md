---
paths:
  /user/emails:
    get:
      summary: Get User Emails
      description: |-
        List email addresses for a user.
        In the final version of the API, this method will return an array of hashes
        with extended information for each email address indicating if the address
        has been verified and if it's primary email address for GitHub.
        Until API v3 is finalized, use the application/vnd.github.v3 media type to
        get other response format.
      operationId: list-email-addresses-for-a-userin-the-final-version-of-the-api-this-method-will-return-an-array-of-h
      x-api-path-slug: useremails-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      responses:
        200:
          description: OK
      tags:
      - User
      - Emails
x-complete: 0
info:
  title: Github Get User Emails
  description: |-
    List email addresses for a user.
    In the final version of the API, this method will return an array of hashes
    with extended information for each email address indicating if the address
    has been verified and if it's primary email address for GitHub.
    Until API v3 is finalized, use the application/vnd.github.v3 media type to
    get other response format.
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
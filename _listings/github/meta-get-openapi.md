---
paths:
  /meta:
    get:
      summary: Get Meta
      description: This gives some information about GitHub.com, the service.
      operationId: this-gives-some-information-about-githubcom-the-service
      x-api-path-slug: meta-get
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
      - Meta
x-complete: 0
info:
  title: Github Get Meta
  description: This gives some information about GitHub.com, the service.
x-streamrank:
  polling_total_time_average: "0.1"
  polling_size_download_average: "521"
  streaming_total_time_average: "0.06"
  streaming_size_download_average: "260.5"
  change_yes: "4"
  change_no: "2336"
  time_percentage: "38"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
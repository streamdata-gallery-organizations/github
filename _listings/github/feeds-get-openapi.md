---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Feeds
  description: |-
    List Feeds.
    GitHub provides several timeline resources in Atom format. The Feeds API
     lists all the feeds available to the authenticating user.
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
  /feeds:
    get:
      summary: Get Feeds
      description: |-
        List Feeds.
        GitHub provides several timeline resources in Atom format. The Feeds API
         lists all the feeds available to the authenticating user.
      operationId: list-feedsgithub-provides-several-timeline-resources-in-atom-format-the-feeds-api-lists-all-the-feed
      x-api-path-slug: feeds-get
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
      - Feeds
x-streamrank:
  polling_total_time_average: "0.1"
  polling_size_download_average: "394.77"
  streaming_total_time_average: "0.06"
  streaming_size_download_average: "197.47"
  change_yes: "4"
  change_no: "2337"
  time_percentage: "38"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
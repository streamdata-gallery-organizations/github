---
paths:
  /orgs/{org}/repos:
    get:
      summary: Get Orgs Org Repos
      description: List repositories for the specified org.
      operationId: list-repositories-for-the-specified-org
      x-api-path-slug: orgsorgrepos-get
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
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Repos
x-complete: 0
info:
  title: Github Get Orgs Org Repos
  description: List repositories for the specified org.
x-streamrank:
  polling_total_time_average: "0.34"
  polling_size_download_average: "155974.55"
  streaming_total_time_average: "0.18"
  streaming_size_download_average: "78054.21"
  change_yes: "4"
  change_no: "2334"
  time_percentage: "46"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
---
paths:
  /repositories:
    get:
      summary: Get Repositories
      description: |-
        List all public repositories.
        This provides a dump of every public repository, in the order that they
        were created.
        Note: Pagination is powered exclusively by the since parameter. is the
        Link header to get the URL for the next page of repositories.
      operationId: list-all-public-repositoriesthis-provides-a-dump-of-every-public-repository-in-the-order-that-theywe
      x-api-path-slug: repositories-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: since
        description: 'The time should be passed in as UTC in the ISO 8601 format:
          YYYY-MM-DDTHH:MM:SSZ'
      responses:
        200:
          description: OK
      tags:
      - Repositories
x-complete: 0
info:
  title: Github Get Repositories
  description: |-
    List all public repositories.
    This provides a dump of every public repository, in the order that they
    were created.
    Note: Pagination is powered exclusively by the since parameter. is the
    Link header to get the URL for the next page of repositories.
x-streamrank:
  polling_total_time_average: "0.28"
  polling_size_download_average: "410971.49"
  streaming_total_time_average: "0.15"
  streaming_size_download_average: "205573.9"
  change_yes: "3"
  change_no: "2330"
  time_percentage: "46"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
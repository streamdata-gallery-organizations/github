---
paths:
  /search/issues:
    get:
      summary: Get Search Issues
      description: Find issues by state and keyword. (This method returns up to 100
        results per page.)
      operationId: find-issues-by-state-and-keyword-this-method-returns-up-to-100-results-per-page
      x-api-path-slug: searchissues-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: order
        description: The sort field
      - in: query
        name: q
        description: 'The q search term can also contain any combination of the supported
          issue search qualifiers:'
      - in: query
        name: sort
        description: The sort field
      responses:
        200:
          description: OK
      tags:
      - Search
      - Issues
x-complete: 0
info:
  title: Github Get Search Issues
  description: Find issues by state and keyword. (This method returns up to 100 results
    per page.)
x-streamrank:
  polling_total_time_average: "0.98"
  polling_size_download_average: "80476.4"
  streaming_total_time_average: "0.51"
  streaming_size_download_average: "40251.83"
  change_yes: "2093"
  change_no: "240"
  time_percentage: "48"
  size_percentage: "50"
  change_percentage: "90"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---
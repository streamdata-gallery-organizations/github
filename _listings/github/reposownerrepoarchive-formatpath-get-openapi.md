---
paths:
  /repos/{owner}/{repo}/{archive_format}/{path}:
    get:
      summary: Get Repos Owner Repo Archive Format Path
      description: |-
        Get archive link.
        This method will return a 302 to a URL to download a tarball or zipball
        archive for a repository. Please make sure your HTTP framework is
        configured to follow redirects or you will need to use the Location header
        to make a second GET request.
        Note: For private repositories, these links are temporary and expire quickly.
      operationId: get-archive-linkthis-method-will-return-a-302-to-a-url-to-download-a-tarball-or-zipballarchive-for-a
      x-api-path-slug: reposownerrepoarchive-formatpath-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: archive_format
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: path
        description: Valid Git reference, defaults to master
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
      - Archives
      - Format
      - Path
x-complete: 0
info:
  title: Github Get Repos Owner Repo Archive Format Path
  description: |-
    Get archive link.
    This method will return a 302 to a URL to download a tarball or zipball
    archive for a repository. Please make sure your HTTP framework is
    configured to follow redirects or you will need to use the Location header
    to make a second GET request.
    Note: For private repositories, these links are temporary and expire quickly.
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
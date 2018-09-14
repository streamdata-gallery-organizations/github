---
paths:
  /repos/{owner}/{repo}/contents/{path}:
    get:
      summary: Get Repos Owner Repo Contents Path
      description: |-
        Get contents.
        This method returns the contents of a file or directory in a repository.
        Files and symlinks support a custom media type for getting the raw content.
        Directories and submodules do not support custom media types.
        Note: This API supports files up to 1 megabyte in size.
        Here can be many outcomes. For details see "http://developer.github.com/v3/repos/contents/"
      operationId: get-contentsthis-method-returns-the-contents-of-a-file-or-directory-in-a-repositoryfiles-and-symlink
      x-api-path-slug: reposownerrepocontentspath-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: path
      - in: query
        name: path
        description: The content path
      - in: query
        name: ref
        description: The String name of the Commit/Branch/Tag
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
      - Contents
      - Path
x-complete: 0
info:
  title: Github Get Repos Owner Repo Contents Path
  description: |-
    Get contents.
    This method returns the contents of a file or directory in a repository.
    Files and symlinks support a custom media type for getting the raw content.
    Directories and submodules do not support custom media types.
    Note: This API supports files up to 1 megabyte in size.
    Here can be many outcomes. For details see "http://developer.github.com/v3/repos/contents/"
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
---
paths:
  /repos/{owner}/{repo}/git/blobs/{shaCode}:
    get:
      summary: Get Repos Owner Repo Git Blobs Shacode
      description: |-
        Get a Blob.
        Since blobs can be any arbitrary binary data, the input and responses for
        the blob API takes an encoding parameter that can be either utf-8 or
        base64. If your data cannot be losslessly sent as a UTF-8 string, you can
        base64 encode it.
      operationId: get-a-blobsince-blobs-can-be-any-arbitrary-binary-data-the-input-and-responses-forthe-blob-api-takes
      x-api-path-slug: reposownerrepogitblobsshacode-get
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
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: SHA-1 code
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Git
      - Blobs
      - Shacode
x-complete: 0
info:
  title: Github Get Repos Owner Repo Git Blobs Shacode
  description: |-
    Get a Blob.
    Since blobs can be any arbitrary binary data, the input and responses for
    the blob API takes an encoding parameter that can be either utf-8 or
    base64. If your data cannot be losslessly sent as a UTF-8 string, you can
    base64 encode it.
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
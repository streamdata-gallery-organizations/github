---
paths:
  /emojis:
    get:
      summary: Get Emojis
      description: Lists all the emojis available to use on GitHub.
      operationId: lists-all-the-emojis-available-to-use-on-github
      x-api-path-slug: emojis-get
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
      - Emojis
  /events:
    get:
      summary: Get Events
      description: List public events.
      operationId: list-public-events
      x-api-path-slug: events-get
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
      - Events
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
  /gists:
    get:
      summary: Get Gists
      description: |-
        List the authenticated user's gists or if called anonymously, this will
        return all public gists.
      operationId: list-the-authenticated-users-gists-or-if-called-anonymously-this-willreturn-all-public-gists
      x-api-path-slug: gists-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: since
        description: Timestamp in ISO 8601 format YYYY-MM-DDTHH:MM:SSZ
      responses:
        200:
          description: OK
      tags:
      - Gists
    post:
      summary: Add Gists
      description: Create a gist.
      operationId: create-a-gist
      x-api-path-slug: gists-post
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
      responses:
        200:
          description: OK
      tags:
      - Gists
x-complete: 0
info:
  title: Github Add Gists
  description: Create a gist.
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
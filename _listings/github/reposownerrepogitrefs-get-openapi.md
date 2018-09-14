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
  /gists/public:
    get:
      summary: Get Gists Public
      description: List all public gists.
      operationId: list-all-public-gists
      x-api-path-slug: gistspublic-get
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
      - Public
  /gists/starred:
    get:
      summary: Get Gists Starred
      description: List the authenticated user's starred gists.
      operationId: list-the-authenticated-users-starred-gists
      x-api-path-slug: gistsstarred-get
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
      - Starred
  /gists/{id}:
    delete:
      summary: Delete Gists
      description: Delete a gist.
      operationId: delete-a-gist
      x-api-path-slug: gistsid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
    get:
      summary: Get Gists
      description: Get a single gist.
      operationId: get-a-single-gist
      x-api-path-slug: gistsid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
    patch:
      summary: Patch Gists
      description: Edit a gist.
      operationId: edit-a-gist
      x-api-path-slug: gistsid-patch
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
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
  /gists/{id}/comments:
    get:
      summary: Get Gists  Comments
      description: List comments on a gist.
      operationId: list-comments-on-a-gist
      x-api-path-slug: gistsidcomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
    post:
      summary: Add Gists  Comments
      description: Create a commen
      operationId: create-a-commen
      x-api-path-slug: gistsidcomments-post
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
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
  /gists/{id}/comments/{commentId}:
    delete:
      summary: Delete Gists  Comments Comment
      description: Delete a comment.
      operationId: delete-a-comment
      x-api-path-slug: gistsidcommentscommentid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
      - Comment
    get:
      summary: Get Gists  Comments Comment
      description: Get a single comment.
      operationId: get-a-single-comment
      x-api-path-slug: gistsidcommentscommentid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
      - Comment
    patch:
      summary: Patch Gists  Comments Comment
      description: Edit a comment.
      operationId: edit-a-comment
      x-api-path-slug: gistsidcommentscommentid-patch
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
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
      - Comment
  /gists/{id}/forks:
    post:
      summary: Add Gists  Forks
      description: Fork a gist.
      operationId: fork-a-gist
      x-api-path-slug: gistsidforks-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Forks
  /gists/{id}/star:
    delete:
      summary: Delete Gists  Star
      description: Unstar a gist.
      operationId: unstar-a-gist
      x-api-path-slug: gistsidstar-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Star
    get:
      summary: Get Gists  Star
      description: Check if a gist is starred.
      operationId: check-if-a-gist-is-starred
      x-api-path-slug: gistsidstar-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Star
    put:
      summary: Put Gists  Star
      description: Star a gist.
      operationId: star-a-gist
      x-api-path-slug: gistsidstar-put
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Star
  /gitignore/templates:
    get:
      summary: Get Gitignore Templates
      description: |-
        Listing available templates.
        List all templates available to pass as an option when creating a repository.
      operationId: listing-available-templateslist-all-templates-available-to-pass-as-an-option-when-creating-a-reposit
      x-api-path-slug: gitignoretemplates-get
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
      - Gitignore
      - Templates
  /gitignore/templates/{language}:
    get:
      summary: Get Gitignore Templates Language
      description: Get a single template.
      operationId: get-a-single-template
      x-api-path-slug: gitignoretemplateslanguage-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: language
      responses:
        200:
          description: OK
      tags:
      - Gitignore
      - Templates
      - Language
  /issues:
    get:
      summary: Get Issues
      description: |-
        List issues.
        List all issues across all the authenticated user's visible repositories.
      operationId: list-issueslist-all-issues-across-all-the-authenticated-users-visible-repositories
      x-api-path-slug: issues-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
      - in: query
        name: filter
        description: Issues assigned to you / created by you / mentioning you / youresubscribed
          to updates for / All issues the authenticated user can see
      - in: query
        name: labels
        description: String list of comma separated Label names
      - in: query
        name: since
        description: 'Optional string of a timestamp in ISO 8601 format: YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: sort
      - in: query
        name: state
      responses:
        200:
          description: OK
      tags:
      - Issues
  /legacy/issues/search/{owner}/{repository}/{state}/{keyword}:
    get:
      summary: Get Legacy Issues Search Owner Repository State Keyword
      description: Find issues by state and keyword.
      operationId: find-issues-by-state-and-keyword
      x-api-path-slug: legacyissuessearchownerrepositorystatekeyword-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: keyword
        description: The search term
      - in: path
        name: owner
      - in: path
        name: repository
      - in: path
        name: state
        description: Indicates the state of the issues to return
      responses:
        200:
          description: OK
      tags:
      - Legacy
      - Issues
      - Search
      - Owner
      - Repository
      - State
      - Keyword
  /legacy/repos/search/{keyword}:
    get:
      summary: Get Legacy Repos Search Keyword
      description: Find repositories by keyword. Note, this legacy method does not
        follow the v3 pagination pattern. This method returns up to 100 results per
        page and pages can be fetched using the start_page parameter.
      operationId: find-repositories-by-keyword-note-this-legacy-method-does-not-follow-the-v3-pagination-pattern-this-
      x-api-path-slug: legacyrepossearchkeyword-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: keyword
        description: The search term
      - in: query
        name: language
        description: Filter results by language
      - in: query
        name: order
        description: The sort field
      - in: query
        name: sort
        description: The sort field
      - in: query
        name: start_page
        description: The page number to fetch
      responses:
        200:
          description: OK
      tags:
      - Legacy
      - Repos
      - Search
      - Keyword
  /legacy/user/email/{email}:
    get:
      summary: Get Legacy User Email Email
      description: This API call is added for compatibility reasons only.
      operationId: this-api-call-is-added-for-compatibility-reasons-only
      x-api-path-slug: legacyuseremailemail-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: email
        description: The email address
      responses:
        200:
          description: OK
      tags:
      - Legacy
      - User
      - Email
      - Email
  /legacy/user/search/{keyword}:
    get:
      summary: Get Legacy User Search Keyword
      description: Find users by keyword.
      operationId: find-users-by-keyword
      x-api-path-slug: legacyusersearchkeyword-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: keyword
        description: The search term
      - in: query
        name: order
        description: The sort field
      - in: query
        name: sort
        description: The sort field
      - in: query
        name: start_page
        description: The page number to fetch
      responses:
        200:
          description: OK
      tags:
      - Legacy
      - User
      - Search
      - Keyword
  /markdown:
    post:
      summary: Add Markdown
      description: Render an arbitrary Markdown document
      operationId: render-an-arbitrary-markdown-document
      x-api-path-slug: markdown-post
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
      - Markdown
  /markdown/raw:
    post:
      summary: Add Markdown Raw
      description: Render a Markdown document in raw mode
      operationId: render-a-markdown-document-in-raw-mode
      x-api-path-slug: markdownraw-post
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
      - Markdown
      - Raw
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
  /networks/{owner}/{repo}/events:
    get:
      summary: Get Networks Owner Repo Events
      description: List public events for a network of repositories.
      operationId: list-public-events-for-a-network-of-repositories
      x-api-path-slug: networksownerrepoevents-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of the owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Networks
      - Owner
      - Repo
      - Events
  /notifications:
    get:
      summary: Get Notifications
      description: |-
        List your notifications.
        List all notifications for the current user, grouped by repository.
      operationId: list-your-notificationslist-all-notifications-for-the-current-user-grouped-by-repository
      x-api-path-slug: notifications-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: all
        description: True to show notifications marked as read
      - in: query
        name: participating
        description: True to show only notifications in which the user is directly
          participatingor mentioned
      - in: query
        name: since
        description: 'The time should be passed in as UTC in the ISO 8601 format:
          YYYY-MM-DDTHH:MM:SSZ'
      responses:
        200:
          description: OK
      tags:
      - Notifications
    put:
      summary: Put Notifications
      description: |-
        Mark as read.
        Marking a notification as "read" removes it from the default view on GitHub.com.
      operationId: mark-as-readmarking-a-notification-as-read-removes-it-from-the-default-view-on-githubcom
      x-api-path-slug: notifications-put
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
      - Notifications
  /notifications/threads/{id}:
    get:
      summary: Get Notifications Threads
      description: View a single thread.
      operationId: view-a-single-thread
      x-api-path-slug: notificationsthreadsid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of thread
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Threads
    patch:
      summary: Patch Notifications Threads
      description: Mark a thread as read
      operationId: mark-a-thread-as-read
      x-api-path-slug: notificationsthreadsid-patch
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of thread
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Threads
  /notifications/threads/{id}/subscription:
    delete:
      summary: Delete Notifications Threads  Subscription
      description: Delete a Thread Subscription.
      operationId: delete-a-thread-subscription
      x-api-path-slug: notificationsthreadsidsubscription-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of thread
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Threads
      - ""
      - Subscription
    get:
      summary: Get Notifications Threads  Subscription
      description: Get a Thread Subscription.
      operationId: get-a-thread-subscription
      x-api-path-slug: notificationsthreadsidsubscription-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of thread
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Threads
      - ""
      - Subscription
    put:
      summary: Put Notifications Threads  Subscription
      description: |-
        Set a Thread Subscription.
        This lets you subscribe to a thread, or ignore it. Subscribing to a thread
        is unnecessary if the user is already subscribed to the repository. Ignoring
        a thread will mute all future notifications (until you comment or get @mentioned).
      operationId: set-a-thread-subscriptionthis-lets-you-subscribe-to-a-thread-or-ignore-it-subscribing-to-a-threadis-
      x-api-path-slug: notificationsthreadsidsubscription-put
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
      - in: path
        name: id
        description: Id of thread
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - Threads
      - ""
      - Subscription
  /orgs/{org}:
    get:
      summary: Get Orgs Org
      description: Get an Organization.
      operationId: get-an-organization
      x-api-path-slug: orgsorg-get
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
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
    patch:
      summary: Patch Orgs Org
      description: Edit an Organization.
      operationId: edit-an-organization
      x-api-path-slug: orgsorg-patch
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
      - in: path
        name: org
        description: Name of organisation
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
  /orgs/{org}/events:
    get:
      summary: Get Orgs Org Events
      description: List public events for an organization.
      operationId: list-public-events-for-an-organization
      x-api-path-slug: orgsorgevents-get
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
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Events
  /orgs/{org}/issues:
    get:
      summary: Get Orgs Org Issues
      description: |-
        List issues.
        List all issues for a given organization for the authenticated user.
      operationId: list-issueslist-all-issues-for-a-given-organization-for-the-authenticated-user
      x-api-path-slug: orgsorgissues-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
      - in: query
        name: filter
        description: Issues assigned to you / created by you / mentioning you / youresubscribed
          to updates for / All issues the authenticated user can see
      - in: query
        name: labels
        description: String list of comma separated Label names
      - in: path
        name: org
        description: Name of organisation
      - in: query
        name: since
        description: 'Optional string of a timestamp in ISO 8601 format: YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: sort
      - in: query
        name: state
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Issues
  /orgs/{org}/members:
    get:
      summary: Get Orgs Org Members
      description: |-
        Members list.
        List all users who are members of an organization. A member is a user tha
        belongs to at least 1 team in the organization. If the authenticated user
        is also an owner of this organization then both concealed and public members
        will be returned. If the requester is not an owner of the organization the
        query will be redirected to the public members list.
      operationId: members-listlist-all-users-who-are-members-of-an-organization-a-member-is-a-user-thabelongs-to-at-le
      x-api-path-slug: orgsorgmembers-get
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
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Members
  /orgs/{org}/members/{username}:
    delete:
      summary: Delete Orgs Org Members Username
      description: |-
        Remove a member.
        Removing a user from this list will remove them from all teams and they
        will no longer have any access to the organization's repositories.
      operationId: remove-a-memberremoving-a-user-from-this-list-will-remove-them-from-all-teams-and-theywill-no-longer
      x-api-path-slug: orgsorgmembersusername-delete
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
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Members
      - Username
    get:
      summary: Get Orgs Org Members Username
      description: Check if a user is, publicly or privately, a member of the organization.
      operationId: check-if-a-user-is-publicly-or-privately-a-member-of-the-organization
      x-api-path-slug: orgsorgmembersusername-get
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
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Members
      - Username
  /orgs/{org}/public_members:
    get:
      summary: Get Orgs Org Public Members
      description: |-
        Public members list.
        Members of an organization can choose to have their membership publicized
        or not.
      operationId: public-members-listmembers-of-an-organization-can-choose-to-have-their-membership-publicizedor-not
      x-api-path-slug: orgsorgpublic-members-get
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
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Public
      - Members
  /orgs/{org}/public_members/{username}:
    delete:
      summary: Delete Orgs Org Public Members Username
      description: Conceal a user's membership.
      operationId: conceal-a-users-membership
      x-api-path-slug: orgsorgpublic-membersusername-delete
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
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Public
      - Members
      - Username
    get:
      summary: Get Orgs Org Public Members Username
      description: Check public membership.
      operationId: check-public-membership
      x-api-path-slug: orgsorgpublic-membersusername-get
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
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Public
      - Members
      - Username
    put:
      summary: Put Orgs Org Public Members Username
      description: Publicize a user's membership.
      operationId: publicize-a-users-membership
      x-api-path-slug: orgsorgpublic-membersusername-put
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
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Public
      - Members
      - Username
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
    post:
      summary: Add Orgs Org Repos
      description: |-
        Create a new repository for the authenticated user. OAuth users must supply
        repo scope.
      operationId: create-a-new-repository-for-the-authenticated-user-oauth-users-must-supplyrepo-scope
      x-api-path-slug: orgsorgrepos-post
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
      - in: path
        name: org
        description: Name of organisation
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Repos
  /orgs/{org}/teams:
    get:
      summary: Get Orgs Org Teams
      description: List teams.
      operationId: list-teams
      x-api-path-slug: orgsorgteams-get
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
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Teams
    post:
      summary: Add Orgs Org Teams
      description: |-
        Create team.
        In order to create a team, the authenticated user must be an owner of organization.
      operationId: create-teamin-order-to-create-a-team-the-authenticated-user-must-be-an-owner-of-organization
      x-api-path-slug: orgsorgteams-post
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
      - in: path
        name: org
        description: Name of organisation
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Teams
  /rate_limit:
    get:
      summary: Get Rate Limit
      description: |-
        Get your current rate limit status
        Note: Accessing this endpoint does not count against your rate limit.
      operationId: get-your-current-rate-limit-statusnote-accessing-this-endpoint-does-not-count-against-your-rate-limi
      x-api-path-slug: rate-limit-get
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
      - Rate
      - Limit
  /repos/{owner}/{repo}:
    delete:
      summary: Delete Repos Owner Repo
      description: |-
        Delete a Repository.
        Deleting a repository requires admin access. If OAuth is used, the delete_repo
        scope is required.
      operationId: delete-a-repositorydeleting-a-repository-requires-admin-access-if-oauth-is-used-the-delete-reposcope
      x-api-path-slug: reposownerrepo-delete
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
    get:
      summary: Get Repos Owner Repo
      description: Get repository.
      operationId: get-repository
      x-api-path-slug: reposownerrepo-get
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
    patch:
      summary: Patch Repos Owner Repo
      description: Edit repository.
      operationId: edit-repository
      x-api-path-slug: reposownerrepo-patch
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
      - in: path
        name: owner
        description: Name of repository owner
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
  /repos/{owner}/{repo}/assignees:
    get:
      summary: Get Repos Owner Repo Assignees
      description: |-
        List assignees.
        This call lists all the available assignees (owner + collaborators) to which
        issues may be assigned.
      operationId: list-assigneesthis-call-lists-all-the-available-assignees-owner--collaborators-to-whichissues-may-be
      x-api-path-slug: reposownerrepoassignees-get
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Assignees
  /repos/{owner}/{repo}/assignees/{assignee}:
    get:
      summary: Get Repos Owner Repo Assignees Assignee
      description: |-
        Check assignee.
        You may also check to see if a particular user is an assignee for a repository.
      operationId: check-assigneeyou-may-also-check-to-see-if-a-particular-user-is-an-assignee-for-a-repository
      x-api-path-slug: reposownerrepoassigneesassignee-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: assignee
        description: Login of the assignee
      - in: path
        name: owner
        description: Name of repository owner
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
      - Assignees
      - Assignee
  /repos/{owner}/{repo}/branches:
    get:
      summary: Get Repos Owner Repo Branches
      description: Get list of branches
      operationId: get-list-of-branches
      x-api-path-slug: reposownerrepobranches-get
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Branches
  /repos/{owner}/{repo}/branches/{branch}:
    get:
      summary: Get Repos Owner Repo Branches Branch
      description: Get Branch
      operationId: get-branch
      x-api-path-slug: reposownerrepobranchesbranch-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: branch
        description: Name of the branch
      - in: path
        name: owner
        description: Name of repository owner
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
      - Branches
      - Branch
  /repos/{owner}/{repo}/collaborators:
    get:
      summary: Get Repos Owner Repo Collaborators
      description: |-
        List.
        When authenticating as an organization owner of an organization-owned
        repository, all organization owners are included in the list of
        collaborators. Otherwise, only users with access to the repository are
        returned in the collaborators list.
      operationId: listwhen-authenticating-as-an-organization-owner-of-an-organizationownedrepository-all-organization-
      x-api-path-slug: reposownerrepocollaborators-get
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Collaborators
  /repos/{owner}/{repo}/collaborators/{user}:
    delete:
      summary: Delete Repos Owner Repo Collaborators User
      description: Remove collaborator.
      operationId: remove-collaborator
      x-api-path-slug: reposownerrepocollaboratorsuser-delete
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
        name: user
        description: Login of the user
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Collaborators
      - User
    get:
      summary: Get Repos Owner Repo Collaborators User
      description: Check if user is a collaborator
      operationId: check-if-user-is-a-collaborator
      x-api-path-slug: reposownerrepocollaboratorsuser-get
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
        name: user
        description: Login of the user
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Collaborators
      - User
    put:
      summary: Put Repos Owner Repo Collaborators User
      description: Add collaborator.
      operationId: add-collaborator
      x-api-path-slug: reposownerrepocollaboratorsuser-put
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
        name: user
        description: Login of the user
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Collaborators
      - User
  /repos/{owner}/{repo}/comments:
    get:
      summary: Get Repos Owner Repo Comments
      description: |-
        List commit comments for a repository.
        Comments are ordered by ascending ID.
      operationId: list-commit-comments-for-a-repositorycomments-are-ordered-by-ascending-id
      x-api-path-slug: reposownerrepocomments-get
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Comments
  /repos/{owner}/{repo}/comments/{commentId}:
    delete:
      summary: Delete Repos Owner Repo Comments Comment
      description: Delete a commit comment
      operationId: delete-a-commit-comment
      x-api-path-slug: reposownerrepocommentscommentid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: owner
        description: Name of repository owner
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
      - Comments
      - Comment
    get:
      summary: Get Repos Owner Repo Comments Comment
      description: Get a single commit comment.
      operationId: get-a-single-commit-comment
      x-api-path-slug: reposownerrepocommentscommentid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: owner
        description: Name of repository owner
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
      - Comments
      - Comment
    patch:
      summary: Patch Repos Owner Repo Comments Comment
      description: Update a commit comment.
      operationId: update-a-commit-comment
      x-api-path-slug: reposownerrepocommentscommentid-patch
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
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: owner
        description: Name of repository owner
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
      - Comments
      - Comment
  /repos/{owner}/{repo}/commits:
    get:
      summary: Get Repos Owner Repo Commits
      description: List commits on a repository.
      operationId: list-commits-on-a-repository
      x-api-path-slug: reposownerrepocommits-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: author
        description: GitHub login, name, or email by which to filter by commit author
      - in: path
        name: owner
        description: Name of repository owner
      - in: query
        name: path
        description: Only commits containing this file path will be returned
      - in: path
        name: repo
        description: Name of repository
      - in: query
        name: sha
        description: Sha or branch to start listing commits from
      - in: query
        name: since
        description: 'The time should be passed in as UTC in the ISO 8601 format:
          YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: until
        description: ISO 8601 Date - Only commits before this date will be returned
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
  /repos/{owner}/{repo}/commits/{ref}/status:
    get:
      summary: Get Repos Owner Repo Commits Ref Status
      description: |-
        Get the combined Status for a specific Ref
        The Combined status endpoint is currently available for developers to preview. During the preview period, the API may change without advance notice. Please see the blog post for full details.
        To access this endpoint during the preview period, you must provide a custom media type in the Accept header:
        application/vnd.github.she-hulk-preview+json
      operationId: get-the-combined-status-for-a-specific-refthe-combined-status-endpoint-is-currently-available-for-de
      x-api-path-slug: reposownerrepocommitsrefstatus-get
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
        name: ref
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
      - Commits
      - Ref
      - Status
  /repos/{owner}/{repo}/commits/{shaCode}:
    get:
      summary: Get Repos Owner Repo Commits Shacode
      description: Get a single commit.
      operationId: get-a-single-commit
      x-api-path-slug: reposownerrepocommitsshacode-get
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
        description: SHA-1 code of the commit
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
      - Shacode
  /repos/{owner}/{repo}/commits/{shaCode}/comments:
    get:
      summary: Get Repos Owner Repo Commits Shacode Comments
      description: List comments for a single commitList comments for a single commit.
      operationId: list-comments-for-a-single-commitlist-comments-for-a-single-commit
      x-api-path-slug: reposownerrepocommitsshacodecomments-get
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
        description: SHA-1 code of the commit
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
      - Shacode
      - Comments
    post:
      summary: Add Repos Owner Repo Commits Shacode Comments
      description: Create a commit comment.
      operationId: create-a-commit-comment
      x-api-path-slug: reposownerrepocommitsshacodecomments-post
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
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: SHA-1 code of the commit
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
      - Shacode
      - Comments
  /repos/{owner}/{repo}/compare/{baseId}...{headId}:
    get:
      summary: Get Repos Owner Repo Compare Base ... Head
      description: Compare two commits
      operationId: compare-two-commits
      x-api-path-slug: reposownerrepocomparebaseid---headid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: baseId
      - in: path
        name: headId
      - in: path
        name: owner
        description: Name of repository owner
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
      - Compare
      - Base
      - '...'
      - Head
  /repos/{owner}/{repo}/contents/{path}:
    delete:
      summary: Delete Repos Owner Repo Contents Path
      description: |-
        Delete a file.
        This method deletes a file in a repository.
      operationId: delete-a-filethis-method-deletes-a-file-in-a-repository
      x-api-path-slug: reposownerrepocontentspath-delete
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
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: path
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
    put:
      summary: Put Repos Owner Repo Contents Path
      description: Create a file.
      operationId: create-a-file
      x-api-path-slug: reposownerrepocontentspath-put
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
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: path
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
  /repos/{owner}/{repo}/contributors:
    get:
      summary: Get Repos Owner Repo Contributors
      description: Get list of contributors.
      operationId: get-list-of-contributors
      x-api-path-slug: reposownerrepocontributors-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: anon
        description: Set to 1 or true to include anonymous contributors in results
      - in: path
        name: owner
        description: Name of repository owner
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
      - Contributors
  /repos/{owner}/{repo}/deployments:
    get:
      summary: Get Repos Owner Repo Deployments
      description: Users with pull access can view deployments for a repository
      operationId: users-with-pull-access-can-view-deployments-for-a-repository
      x-api-path-slug: reposownerrepodeployments-get
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Deployments
    post:
      summary: Add Repos Owner Repo Deployments
      description: Users with push access can create a deployment for a given ref
      operationId: users-with-push-access-can-create-a-deployment-for-a-given-ref
      x-api-path-slug: reposownerrepodeployments-post
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
      - in: path
        name: owner
        description: Name of repository owner
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
      - Deployments
  /repos/{owner}/{repo}/deployments/{id}/statuses:
    get:
      summary: Get Repos Owner Repo Deployments  Statuses
      description: Users with pull access can view deployment statuses for a deployment
      operationId: users-with-pull-access-can-view-deployment-statuses-for-a-deployment
      x-api-path-slug: reposownerrepodeploymentsidstatuses-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: The Deployment ID to list the statuses from
      - in: path
        name: owner
        description: Name of repository owner
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
      - Deployments
      - ""
      - Statuses
    post:
      summary: Add Repos Owner Repo Deployments  Statuses
      description: |-
        Create a Deployment Status
        Users with push access can create deployment statuses for a given deployment:
      operationId: create-a-deployment-statususers-with-push-access-can-create-deployment-statuses-for-a-given-deployme
      x-api-path-slug: reposownerrepodeploymentsidstatuses-post
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
      - in: path
        name: id
        description: The Deployment ID to list the statuses from
      - in: path
        name: owner
        description: Name of repository owner
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
      - Deployments
      - ""
      - Statuses
  /repos/{owner}/{repo}/downloads:
    get:
      summary: Get Repos Owner Repo Downloads
      description: Deprecated. List downloads for a repository.
      operationId: deprecated-list-downloads-for-a-repository
      x-api-path-slug: reposownerrepodownloads-get
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Downloads
  /repos/{owner}/{repo}/downloads/{downloadId}:
    delete:
      summary: Delete Repos Owner Repo Downloads Download
      description: Deprecated. Delete a download.
      operationId: deprecated-delete-a-download
      x-api-path-slug: reposownerrepodownloadsdownloadid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: downloadId
        description: Id of download
      - in: path
        name: owner
        description: Name of repository owner
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
      - Downloads
      - Download
    get:
      summary: Get Repos Owner Repo Downloads Download
      description: Deprecated. Get a single download.
      operationId: deprecated-get-a-single-download
      x-api-path-slug: reposownerrepodownloadsdownloadid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: downloadId
        description: Id of download
      - in: path
        name: owner
        description: Name of repository owner
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
      - Downloads
      - Download
  /repos/{owner}/{repo}/events:
    get:
      summary: Get Repos Owner Repo Events
      description: Get list of repository events.
      operationId: get-list-of-repository-events
      x-api-path-slug: reposownerrepoevents-get
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Events
  /repos/{owner}/{repo}/forks:
    get:
      summary: Get Repos Owner Repo Forks
      description: List forks.
      operationId: list-forks
      x-api-path-slug: reposownerrepoforks-get
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
      - in: query
        name: sort
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Forks
    post:
      summary: Add Repos Owner Repo Forks
      description: |-
        Create a fork.
        Forking a Repository happens asynchronously. Therefore, you may have to wai
        a short period before accessing the git objects. If this takes longer than 5
        minutes, be sure to contact Support.
      operationId: create-a-forkforking-a-repository-happens-asynchronously-therefore-you-may-have-to-waia-short-period
      x-api-path-slug: reposownerrepoforks-post
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
      - in: path
        name: owner
        description: Name of repository owner
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
      - Forks
  /repos/{owner}/{repo}/git/blobs:
    post:
      summary: Add Repos Owner Repo Git Blobs
      description: Create a Blob.
      operationId: create-a-blob
      x-api-path-slug: reposownerrepogitblobs-post
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
      - in: path
        name: owner
        description: Name of repository owner
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
      - Git
      - Blobs
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
  /repos/{owner}/{repo}/git/commits:
    post:
      summary: Add Repos Owner Repo Git Commits
      description: Create a Commit.
      operationId: create-a-commit
      x-api-path-slug: reposownerrepogitcommits-post
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
      - in: path
        name: owner
        description: Name of repository owner
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
      - Git
      - Commits
  /repos/{owner}/{repo}/git/commits/{shaCode}:
    get:
      summary: Get Repos Owner Repo Git Commits Shacode
      description: Get a Commit.
      operationId: get-a-commit
      x-api-path-slug: reposownerrepogitcommitsshacode-get
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
      - Commits
      - Shacode
  /repos/{owner}/{repo}/git/refs:
    get:
      summary: Get Repos Owner Repo Git Refs
      description: Get all References
      operationId: get-all-references
      x-api-path-slug: reposownerrepogitrefs-get
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
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Git
      - Refs
x-complete: 0
info:
  title: Github Get Repos Owner Repo Git Refs
  description: Get all References
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
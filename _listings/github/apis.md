---
name: GitHub
x-slug: github
description: With a community of more than 10 million people, developers can discover,
  use and contribute to over 24 million projects using a powerful, collaborative workflow.    Whether
  using GitHub.com or your own instance of GitHub Enterprise, you can integrate ...
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
x-kinRank: "10"
x-alexaRank: "70"
tags: GitHub
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/apis.md
specificationVersion: "0.14"
apis:
- name: Github Get Emojis
  x-api-slug: github
  description: Lists all the emojis available to use on GitHub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////emojis
  tags: Emojis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/emojis-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/emojis-get-openapi.md
- name: Github Get Events
  x-api-slug: github
  description: List public events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////events
  tags: Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/events-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/events-get-openapi.md
- name: Github Get Feeds
  x-api-slug: github
  description: |-
    List Feeds.
    GitHub provides several timeline resources in Atom format. The Feeds API
     lists all the feeds available to the authenticating user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////feeds
  tags: Feeds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/feeds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/feeds-get-openapi.md
- name: Github Get Gists
  x-api-slug: github
  description: |-
    List the authenticated user's gists or if called anonymously, this will
    return all public gists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists
  tags: Gists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gists-get-openapi.md
- name: Github Add Gists
  x-api-slug: github
  description: Create a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists
  tags: Gists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gists-post-openapi.md
- name: Github Get Gists Public
  x-api-slug: github
  description: List all public gists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/public
  tags: Gists, Public
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistspublic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistspublic-get-openapi.md
- name: Github Get Gists Starred
  x-api-slug: github
  description: List the authenticated user's starred gists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/starred
  tags: Gists, Starred
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsstarred-get-openapi.md
- name: Github Delete Gists
  x-api-slug: github
  description: Delete a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}
  tags: Gists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsid-delete-openapi.md
- name: Github Get Gists
  x-api-slug: github
  description: Get a single gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}
  tags: Gists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsid-get-openapi.md
- name: Github Patch Gists
  x-api-slug: github
  description: Edit a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}
  tags: Gists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsid-patch-openapi.md
- name: Github Get Gists  Comments
  x-api-slug: github
  description: List comments on a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments
  tags: Gists, , Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidcomments-get-openapi.md
- name: Github Add Gists  Comments
  x-api-slug: github
  description: Create a commen
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments
  tags: Gists, , Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidcomments-post-openapi.md
- name: Github Delete Gists  Comments Comment
  x-api-slug: github
  description: Delete a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments/{commentId}
  tags: Gists, , Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidcommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidcommentscommentid-delete-openapi.md
- name: Github Get Gists  Comments Comment
  x-api-slug: github
  description: Get a single comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments/{commentId}
  tags: Gists, , Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidcommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidcommentscommentid-get-openapi.md
- name: Github Patch Gists  Comments Comment
  x-api-slug: github
  description: Edit a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments/{commentId}
  tags: Gists, , Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidcommentscommentid-patch-openapi.md
- name: Github Add Gists  Forks
  x-api-slug: github
  description: Fork a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/forks
  tags: Gists, , Forks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidforks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidforks-post-openapi.md
- name: Github Delete Gists  Star
  x-api-slug: github
  description: Unstar a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/star
  tags: Gists, , Star
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidstar-delete-openapi.md
- name: Github Get Gists  Star
  x-api-slug: github
  description: Check if a gist is starred.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/star
  tags: Gists, , Star
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidstar-get-openapi.md
- name: Github Put Gists  Star
  x-api-slug: github
  description: Star a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/star
  tags: Gists, , Star
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gistsidstar-put-openapi.md
- name: Github Get Gitignore Templates
  x-api-slug: github
  description: |-
    Listing available templates.
    List all templates available to pass as an option when creating a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gitignore/templates
  tags: Gitignore, Templates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gitignoretemplates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gitignoretemplates-get-openapi.md
- name: Github Get Gitignore Templates Language
  x-api-slug: github
  description: Get a single template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gitignore/templates/{language}
  tags: Gitignore, Templates, Language
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gitignoretemplateslanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/gitignoretemplateslanguage-get-openapi.md
- name: Github Get Issues
  x-api-slug: github
  description: |-
    List issues.
    List all issues across all the authenticated user's visible repositories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////issues
  tags: Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/issues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/issues-get-openapi.md
- name: Github Get Legacy Issues Search Owner Repository State Keyword
  x-api-slug: github
  description: Find issues by state and keyword.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////legacy/issues/search/{owner}/{repository}/{state}/{keyword}
  tags: Legacy, Issues, Search, Owner, Repository, State, Keyword
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/legacyissuessearchownerrepositorystatekeyword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/legacyissuessearchownerrepositorystatekeyword-get-openapi.md
- name: Github Get Legacy Repos Search Keyword
  x-api-slug: github
  description: Find repositories by keyword. Note, this legacy method does not follow
    the v3 pagination pattern. This method returns up to 100 results per page and
    pages can be fetched using the start_page parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////legacy/repos/search/{keyword}
  tags: Legacy, Repos, Search, Keyword
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/legacyrepossearchkeyword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/legacyrepossearchkeyword-get-openapi.md
- name: Github Get Legacy User Email Email
  x-api-slug: github
  description: This API call is added for compatibility reasons only.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////legacy/user/email/{email}
  tags: Legacy, User, Email, Email
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/legacyuseremailemail-get-openapi.md
- name: Github Get Legacy User Search Keyword
  x-api-slug: github
  description: Find users by keyword.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////legacy/user/search/{keyword}
  tags: Legacy, User, Search, Keyword
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/legacyusersearchkeyword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/legacyusersearchkeyword-get-openapi.md
- name: Github Add Markdown
  x-api-slug: github
  description: Render an arbitrary Markdown document
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////markdown
  tags: Markdown
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/markdown-post-openapi.md
- name: Github Add Markdown Raw
  x-api-slug: github
  description: Render a Markdown document in raw mode
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////markdown/raw
  tags: Markdown, Raw
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/markdownraw-post-openapi.md
- name: Github Get Meta
  x-api-slug: github
  description: This gives some information about GitHub.com, the service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////meta
  tags: Meta
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/meta-get-openapi.md
- name: Github Get Networks Owner Repo Events
  x-api-slug: github
  description: List public events for a network of repositories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////networks/{owner}/{repo}/events
  tags: Networks, Owner, Repo, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/networksownerrepoevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/networksownerrepoevents-get-openapi.md
- name: Github Get Notifications
  x-api-slug: github
  description: |-
    List your notifications.
    List all notifications for the current user, grouped by repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////notifications
  tags: Notifications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notifications-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notifications-get-openapi.md
- name: Github Put Notifications
  x-api-slug: github
  description: |-
    Mark as read.
    Marking a notification as "read" removes it from the default view on GitHub.com.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////notifications
  tags: Notifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notifications-put-openapi.md
- name: Github Get Notifications Threads
  x-api-slug: github
  description: View a single thread.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////notifications/threads/{id}
  tags: Notifications, Threads
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notificationsthreadsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notificationsthreadsid-get-openapi.md
- name: Github Patch Notifications Threads
  x-api-slug: github
  description: Mark a thread as read
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////notifications/threads/{id}
  tags: Notifications, Threads
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notificationsthreadsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notificationsthreadsid-patch-openapi.md
- name: Github Delete Notifications Threads  Subscription
  x-api-slug: github
  description: Delete a Thread Subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////notifications/threads/{id}/subscription
  tags: Notifications, Threads, , Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notificationsthreadsidsubscription-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notificationsthreadsidsubscription-delete-openapi.md
- name: Github Get Notifications Threads  Subscription
  x-api-slug: github
  description: Get a Thread Subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////notifications/threads/{id}/subscription
  tags: Notifications, Threads, , Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notificationsthreadsidsubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notificationsthreadsidsubscription-get-openapi.md
- name: Github Put Notifications Threads  Subscription
  x-api-slug: github
  description: |-
    Set a Thread Subscription.
    This lets you subscribe to a thread, or ignore it. Subscribing to a thread
    is unnecessary if the user is already subscribed to the repository. Ignoring
    a thread will mute all future notifications (until you comment or get @mentioned).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////notifications/threads/{id}/subscription
  tags: Notifications, Threads, , Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/notificationsthreadsidsubscription-put-openapi.md
- name: Github Get Orgs Org
  x-api-slug: github
  description: Get an Organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}
  tags: Orgs, Org
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorg-get-openapi.md
- name: Github Patch Orgs Org
  x-api-slug: github
  description: Edit an Organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}
  tags: Orgs, Org
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorg-patch-openapi.md
- name: Github Get Orgs Org Events
  x-api-slug: github
  description: List public events for an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/events
  tags: Orgs, Org, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgevents-get-openapi.md
- name: Github Get Orgs Org Issues
  x-api-slug: github
  description: |-
    List issues.
    List all issues for a given organization for the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/issues
  tags: Orgs, Org, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgissues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgissues-get-openapi.md
- name: Github Get Orgs Org Members
  x-api-slug: github
  description: |-
    Members list.
    List all users who are members of an organization. A member is a user tha
    belongs to at least 1 team in the organization. If the authenticated user
    is also an owner of this organization then both concealed and public members
    will be returned. If the requester is not an owner of the organization the
    query will be redirected to the public members list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/members
  tags: Orgs, Org, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgmembers-get-openapi.md
- name: Github Delete Orgs Org Members Username
  x-api-slug: github
  description: |-
    Remove a member.
    Removing a user from this list will remove them from all teams and they
    will no longer have any access to the organization's repositories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/members/{username}
  tags: Orgs, Org, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgmembersusername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgmembersusername-delete-openapi.md
- name: Github Get Orgs Org Members Username
  x-api-slug: github
  description: Check if a user is, publicly or privately, a member of the organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/members/{username}
  tags: Orgs, Org, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgmembersusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgmembersusername-get-openapi.md
- name: Github Get Orgs Org Public Members
  x-api-slug: github
  description: |-
    Public members list.
    Members of an organization can choose to have their membership publicized
    or not.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/public_members
  tags: Orgs, Org, Public, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgpublic-members-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgpublic-members-get-openapi.md
- name: Github Delete Orgs Org Public Members Username
  x-api-slug: github
  description: Conceal a user's membership.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/public_members/{username}
  tags: Orgs, Org, Public, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgpublic-membersusername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgpublic-membersusername-delete-openapi.md
- name: Github Get Orgs Org Public Members Username
  x-api-slug: github
  description: Check public membership.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/public_members/{username}
  tags: Orgs, Org, Public, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgpublic-membersusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgpublic-membersusername-get-openapi.md
- name: Github Put Orgs Org Public Members Username
  x-api-slug: github
  description: Publicize a user's membership.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/public_members/{username}
  tags: Orgs, Org, Public, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgpublic-membersusername-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgpublic-membersusername-put-openapi.md
- name: Github Get Orgs Org Repos
  x-api-slug: github
  description: List repositories for the specified org.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/repos
  tags: Orgs, Org, Repos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgrepos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgrepos-get-openapi.md
- name: Github Add Orgs Org Repos
  x-api-slug: github
  description: |-
    Create a new repository for the authenticated user. OAuth users must supply
    repo scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/repos
  tags: Orgs, Org, Repos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgrepos-post-openapi.md
- name: Github Get Orgs Org Teams
  x-api-slug: github
  description: List teams.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/teams
  tags: Orgs, Org, Teams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgteams-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgteams-get-openapi.md
- name: Github Add Orgs Org Teams
  x-api-slug: github
  description: |-
    Create team.
    In order to create a team, the authenticated user must be an owner of organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/teams
  tags: Orgs, Org, Teams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/orgsorgteams-post-openapi.md
- name: Github Get Rate Limit
  x-api-slug: github
  description: |-
    Get your current rate limit status
    Note: Accessing this endpoint does not count against your rate limit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////rate_limit
  tags: Rate, Limit
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/rate-limit-get-openapi.md
- name: Github Delete Repos Owner Repo
  x-api-slug: github
  description: |-
    Delete a Repository.
    Deleting a repository requires admin access. If OAuth is used, the delete_repo
    scope is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}
  tags: Repos, Owner, Repo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepo-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepo-delete-openapi.md
- name: Github Get Repos Owner Repo
  x-api-slug: github
  description: Get repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}
  tags: Repos, Owner, Repo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepo-get-openapi.md
- name: Github Patch Repos Owner Repo
  x-api-slug: github
  description: Edit repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}
  tags: Repos, Owner, Repo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepo-patch-openapi.md
- name: Github Get Repos Owner Repo Assignees
  x-api-slug: github
  description: |-
    List assignees.
    This call lists all the available assignees (owner + collaborators) to which
    issues may be assigned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/assignees
  tags: Repos, Owner, Repo, Assignees
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoassignees-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoassignees-get-openapi.md
- name: Github Get Repos Owner Repo Assignees Assignee
  x-api-slug: github
  description: |-
    Check assignee.
    You may also check to see if a particular user is an assignee for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/assignees/{assignee}
  tags: Repos, Owner, Repo, Assignees, Assignee
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoassigneesassignee-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoassigneesassignee-get-openapi.md
- name: Github Get Repos Owner Repo Branches
  x-api-slug: github
  description: Get list of branches
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/branches
  tags: Repos, Owner, Repo, Branches
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepobranches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepobranches-get-openapi.md
- name: Github Get Repos Owner Repo Branches Branch
  x-api-slug: github
  description: Get Branch
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/branches/{branch}
  tags: Repos, Owner, Repo, Branches, Branch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepobranchesbranch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepobranchesbranch-get-openapi.md
- name: Github Get Repos Owner Repo Collaborators
  x-api-slug: github
  description: |-
    List.
    When authenticating as an organization owner of an organization-owned
    repository, all organization owners are included in the list of
    collaborators. Otherwise, only users with access to the repository are
    returned in the collaborators list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/collaborators
  tags: Repos, Owner, Repo, Collaborators
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocollaborators-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocollaborators-get-openapi.md
- name: Github Delete Repos Owner Repo Collaborators User
  x-api-slug: github
  description: Remove collaborator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/collaborators/{user}
  tags: Repos, Owner, Repo, Collaborators, User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocollaboratorsuser-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocollaboratorsuser-delete-openapi.md
- name: Github Get Repos Owner Repo Collaborators User
  x-api-slug: github
  description: Check if user is a collaborator
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/collaborators/{user}
  tags: Repos, Owner, Repo, Collaborators, User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocollaboratorsuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocollaboratorsuser-get-openapi.md
- name: Github Put Repos Owner Repo Collaborators User
  x-api-slug: github
  description: Add collaborator.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/collaborators/{user}
  tags: Repos, Owner, Repo, Collaborators, User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocollaboratorsuser-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocollaboratorsuser-put-openapi.md
- name: Github Get Repos Owner Repo Comments
  x-api-slug: github
  description: |-
    List commit comments for a repository.
    Comments are ordered by ascending ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/comments
  tags: Repos, Owner, Repo, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocomments-get-openapi.md
- name: Github Delete Repos Owner Repo Comments Comment
  x-api-slug: github
  description: Delete a commit comment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/comments/{commentId}
  tags: Repos, Owner, Repo, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommentscommentid-delete-openapi.md
- name: Github Get Repos Owner Repo Comments Comment
  x-api-slug: github
  description: Get a single commit comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/comments/{commentId}
  tags: Repos, Owner, Repo, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommentscommentid-get-openapi.md
- name: Github Patch Repos Owner Repo Comments Comment
  x-api-slug: github
  description: Update a commit comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/comments/{commentId}
  tags: Repos, Owner, Repo, Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommentscommentid-patch-openapi.md
- name: Github Get Repos Owner Repo Commits
  x-api-slug: github
  description: List commits on a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits
  tags: Repos, Owner, Repo, Commits
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommits-get-openapi.md
- name: Github Get Repos Owner Repo Commits Ref Status
  x-api-slug: github
  description: |-
    Get the combined Status for a specific Ref
    The Combined status endpoint is currently available for developers to preview. During the preview period, the API may change without advance notice. Please see the blog post for full details.
    To access this endpoint during the preview period, you must provide a custom media type in the Accept header:
    application/vnd.github.she-hulk-preview+json
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits/{ref}/status
  tags: Repos, Owner, Repo, Commits, Ref, Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommitsrefstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommitsrefstatus-get-openapi.md
- name: Github Get Repos Owner Repo Commits Shacode
  x-api-slug: github
  description: Get a single commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits/{shaCode}
  tags: Repos, Owner, Repo, Commits, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommitsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommitsshacode-get-openapi.md
- name: Github Get Repos Owner Repo Commits Shacode Comments
  x-api-slug: github
  description: List comments for a single commitList comments for a single commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits/{shaCode}/comments
  tags: Repos, Owner, Repo, Commits, Shacode, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommitsshacodecomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommitsshacodecomments-get-openapi.md
- name: Github Add Repos Owner Repo Commits Shacode Comments
  x-api-slug: github
  description: Create a commit comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits/{shaCode}/comments
  tags: Repos, Owner, Repo, Commits, Shacode, Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocommitsshacodecomments-post-openapi.md
- name: Github Get Repos Owner Repo Compare Base ... Head
  x-api-slug: github
  description: Compare two commits
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/compare/{baseId}...{headId}
  tags: Repos, Owner, Repo, Compare, Base, ..., Head
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocomparebaseidheadid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocomparebaseidheadid-get-openapi.md
- name: Github Delete Repos Owner Repo Contents Path
  x-api-slug: github
  description: |-
    Delete a file.
    This method deletes a file in a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/contents/{path}
  tags: Repos, Owner, Repo, Contents, Path
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocontentspath-delete-openapi.md
- name: Github Get Repos Owner Repo Contents Path
  x-api-slug: github
  description: |-
    Get contents.
    This method returns the contents of a file or directory in a repository.
    Files and symlinks support a custom media type for getting the raw content.
    Directories and submodules do not support custom media types.
    Note: This API supports files up to 1 megabyte in size.
    Here can be many outcomes. For details see "http://developer.github.com/v3/repos/contents/"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/contents/{path}
  tags: Repos, Owner, Repo, Contents, Path
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocontentspath-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocontentspath-get-openapi.md
- name: Github Put Repos Owner Repo Contents Path
  x-api-slug: github
  description: Create a file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/contents/{path}
  tags: Repos, Owner, Repo, Contents, Path
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocontentspath-put-openapi.md
- name: Github Get Repos Owner Repo Contributors
  x-api-slug: github
  description: Get list of contributors.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/contributors
  tags: Repos, Owner, Repo, Contributors
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocontributors-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepocontributors-get-openapi.md
- name: Github Get Repos Owner Repo Deployments
  x-api-slug: github
  description: Users with pull access can view deployments for a repository
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/deployments
  tags: Repos, Owner, Repo, Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodeployments-get-openapi.md
- name: Github Add Repos Owner Repo Deployments
  x-api-slug: github
  description: Users with push access can create a deployment for a given ref
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/deployments
  tags: Repos, Owner, Repo, Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodeployments-post-openapi.md
- name: Github Get Repos Owner Repo Deployments  Statuses
  x-api-slug: github
  description: Users with pull access can view deployment statuses for a deployment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/deployments/{id}/statuses
  tags: Repos, Owner, Repo, Deployments, , Statuses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodeploymentsidstatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodeploymentsidstatuses-get-openapi.md
- name: Github Add Repos Owner Repo Deployments  Statuses
  x-api-slug: github
  description: |-
    Create a Deployment Status
    Users with push access can create deployment statuses for a given deployment:
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/deployments/{id}/statuses
  tags: Repos, Owner, Repo, Deployments, , Statuses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodeploymentsidstatuses-post-openapi.md
- name: Github Get Repos Owner Repo Downloads
  x-api-slug: github
  description: Deprecated. List downloads for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/downloads
  tags: Repos, Owner, Repo, Downloads
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodownloads-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodownloads-get-openapi.md
- name: Github Delete Repos Owner Repo Downloads Download
  x-api-slug: github
  description: Deprecated. Delete a download.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/downloads/{downloadId}
  tags: Repos, Owner, Repo, Downloads, Download
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodownloadsdownloadid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodownloadsdownloadid-delete-openapi.md
- name: Github Get Repos Owner Repo Downloads Download
  x-api-slug: github
  description: Deprecated. Get a single download.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/downloads/{downloadId}
  tags: Repos, Owner, Repo, Downloads, Download
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodownloadsdownloadid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepodownloadsdownloadid-get-openapi.md
- name: Github Get Repos Owner Repo Events
  x-api-slug: github
  description: Get list of repository events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/events
  tags: Repos, Owner, Repo, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoevents-get-openapi.md
- name: Github Get Repos Owner Repo Forks
  x-api-slug: github
  description: List forks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/forks
  tags: Repos, Owner, Repo, Forks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoforks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoforks-get-openapi.md
- name: Github Add Repos Owner Repo Forks
  x-api-slug: github
  description: |-
    Create a fork.
    Forking a Repository happens asynchronously. Therefore, you may have to wai
    a short period before accessing the git objects. If this takes longer than 5
    minutes, be sure to contact Support.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/forks
  tags: Repos, Owner, Repo, Forks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoforks-post-openapi.md
- name: Github Add Repos Owner Repo Git Blobs
  x-api-slug: github
  description: Create a Blob.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/blobs
  tags: Repos, Owner, Repo, Git, Blobs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitblobs-post-openapi.md
- name: Github Get Repos Owner Repo Git Blobs Shacode
  x-api-slug: github
  description: |-
    Get a Blob.
    Since blobs can be any arbitrary binary data, the input and responses for
    the blob API takes an encoding parameter that can be either utf-8 or
    base64. If your data cannot be losslessly sent as a UTF-8 string, you can
    base64 encode it.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/blobs/{shaCode}
  tags: Repos, Owner, Repo, Git, Blobs, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitblobsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitblobsshacode-get-openapi.md
- name: Github Add Repos Owner Repo Git Commits
  x-api-slug: github
  description: Create a Commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/commits
  tags: Repos, Owner, Repo, Git, Commits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitcommits-post-openapi.md
- name: Github Get Repos Owner Repo Git Commits Shacode
  x-api-slug: github
  description: Get a Commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/commits/{shaCode}
  tags: Repos, Owner, Repo, Git, Commits, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitcommitsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitcommitsshacode-get-openapi.md
- name: Github Get Repos Owner Repo Git Refs
  x-api-slug: github
  description: Get all References
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs
  tags: Repos, Owner, Repo, Git, Refs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitrefs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitrefs-get-openapi.md
- name: Github Add Repos Owner Repo Git Refs
  x-api-slug: github
  description: Create a Reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs
  tags: Repos, Owner, Repo, Git, Refs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitrefs-post-openapi.md
- name: Github Delete Repos Owner Repo Git Refs Ref
  x-api-slug: github
  description: "Delete a Reference\nExample: Deleting a branch: DELETE /repos/octocat/Hello-World/git/refs/heads/feature-a
    \nExample: Deleting a tag:        DELETE /repos/octocat/Hello-World/git/refs/tags/v1.0"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs/{ref}
  tags: Repos, Owner, Repo, Git, Refs, Ref
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitrefsref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitrefsref-delete-openapi.md
- name: Github Get Repos Owner Repo Git Refs Ref
  x-api-slug: github
  description: Get a Reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs/{ref}
  tags: Repos, Owner, Repo, Git, Refs, Ref
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitrefsref-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitrefsref-get-openapi.md
- name: Github Patch Repos Owner Repo Git Refs Ref
  x-api-slug: github
  description: Update a Reference
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/refs/{ref}
  tags: Repos, Owner, Repo, Git, Refs, Ref
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogitrefsref-patch-openapi.md
- name: Github Add Repos Owner Repo Git Tags
  x-api-slug: github
  description: |-
    Create a Tag Object.
    Note that creating a tag object does not create the reference that makes a
    tag in Git. If you want to create an annotated tag in Git, you have to do
    this call to create the tag object, and then create the refs/tags/[tag]
    reference. If you want to create a lightweight tag, you only have to create
    the tag reference - this call would be unnecessary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/tags
  tags: Repos, Owner, Repo, Git, Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogittags-post-openapi.md
- name: Github Get Repos Owner Repo Git Tags Shacode
  x-api-slug: github
  description: Get a Tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/tags/{shaCode}
  tags: Repos, Owner, Repo, Git, Tags, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogittagsshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogittagsshacode-get-openapi.md
- name: Github Add Repos Owner Repo Git Trees
  x-api-slug: github
  description: |-
    Create a Tree.
    The tree creation API will take nested entries as well. If both a tree and
    a nested path modifying that tree are specified, it will overwrite the
    contents of that tree with the new path contents and write a new tree out.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/trees
  tags: Repos, Owner, Repo, Git, Trees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogittrees-post-openapi.md
- name: Github Get Repos Owner Repo Git Trees Shacode
  x-api-slug: github
  description: Get a Tree.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/git/trees/{shaCode}
  tags: Repos, Owner, Repo, Git, Trees, Shacode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogittreesshacode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepogittreesshacode-get-openapi.md
- name: Github Get Repos Owner Repo Hooks
  x-api-slug: github
  description: Get list of hooks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/hooks
  tags: Repos, Owner, Repo, Hooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohooks-get-openapi.md
- name: Github Add Repos Owner Repo Hooks
  x-api-slug: github
  description: Create a hook.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/hooks
  tags: Repos, Owner, Repo, Hooks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohooks-post-openapi.md
- name: Github Delete Repos Owner Repo Hooks Hook
  x-api-slug: github
  description: Delete a hook.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/hooks/{hookId}
  tags: Repos, Owner, Repo, Hooks, Hook
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohookshookid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohookshookid-delete-openapi.md
- name: Github Get Repos Owner Repo Hooks Hook
  x-api-slug: github
  description: Get single hook.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/hooks/{hookId}
  tags: Repos, Owner, Repo, Hooks, Hook
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohookshookid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohookshookid-get-openapi.md
- name: Github Patch Repos Owner Repo Hooks Hook
  x-api-slug: github
  description: Edit a hook.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/hooks/{hookId}
  tags: Repos, Owner, Repo, Hooks, Hook
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohookshookid-patch-openapi.md
- name: Github Add Repos Owner Repo Hooks Hook Tests
  x-api-slug: github
  description: |-
    Test a push hook.
    This will trigger the hook with the latest push to the current repository
    if the hook is subscribed to push events. If the hook is not subscribed
    to push events, the server will respond with 204 but no test POST will
    be generated.
    Note: Previously /repos/:owner/:repo/hooks/:id/tes
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/hooks/{hookId}/tests
  tags: Repos, Owner, Repo, Hooks, Hook, Tests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohookshookidtests-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepohookshookidtests-post-openapi.md
- name: Github Get Repos Owner Repo Issues
  x-api-slug: github
  description: List issues for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues
  tags: Repos, Owner, Repo, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissues-get-openapi.md
- name: Github Add Repos Owner Repo Issues
  x-api-slug: github
  description: |-
    Create an issue.
    Any user with pull access to a repository can create an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues
  tags: Repos, Owner, Repo, Issues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissues-post-openapi.md
- name: Github Get Repos Owner Repo Issues Comments
  x-api-slug: github
  description: List comments in a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments
  tags: Repos, Owner, Repo, Issues, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuescomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuescomments-get-openapi.md
- name: Github Delete Repos Owner Repo Issues Comments Comment
  x-api-slug: github
  description: Delete a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments/{commentId}
  tags: Repos, Owner, Repo, Issues, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuescommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuescommentscommentid-delete-openapi.md
- name: Github Get Repos Owner Repo Issues Comments Comment
  x-api-slug: github
  description: Get a single comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments/{commentId}
  tags: Repos, Owner, Repo, Issues, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuescommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuescommentscommentid-get-openapi.md
- name: Github Patch Repos Owner Repo Issues Comments Comment
  x-api-slug: github
  description: Edit a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments/{commentId}
  tags: Repos, Owner, Repo, Issues, Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuescommentscommentid-patch-openapi.md
- name: Github Get Repos Owner Repo Issues Events
  x-api-slug: github
  description: List issue events for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/events
  tags: Repos, Owner, Repo, Issues, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesevents-get-openapi.md
- name: Github Get Repos Owner Repo Issues Events Event
  x-api-slug: github
  description: Get a single event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/events/{eventId}
  tags: Repos, Owner, Repo, Issues, Events, Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissueseventseventid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissueseventseventid-get-openapi.md
- name: Github Get Repos Owner Repo Issues Number
  x-api-slug: github
  description: Get a single issue
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}
  tags: Repos, Owner, Repo, Issues, Number
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumber-get-openapi.md
- name: Github Patch Repos Owner Repo Issues Number
  x-api-slug: github
  description: |-
    Edit an issue.
    Issue owners and users with push access can edit an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}
  tags: Repos, Owner, Repo, Issues, Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumber-patch-openapi.md
- name: Github Get Repos Owner Repo Issues Number Comments
  x-api-slug: github
  description: List comments on an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/comments
  tags: Repos, Owner, Repo, Issues, Number, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumbercomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumbercomments-get-openapi.md
- name: Github Add Repos Owner Repo Issues Number Comments
  x-api-slug: github
  description: Create a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/comments
  tags: Repos, Owner, Repo, Issues, Number, Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumbercomments-post-openapi.md
- name: Github Get Repos Owner Repo Issues Number Events
  x-api-slug: github
  description: List events for an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/events
  tags: Repos, Owner, Repo, Issues, Number, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberevents-get-openapi.md
- name: Github Delete Repos Owner Repo Issues Number Labels
  x-api-slug: github
  description: Remove all labels from an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels
  tags: Repos, Owner, Repo, Issues, Number, Labels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberlabels-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberlabels-delete-openapi.md
- name: Github Get Repos Owner Repo Issues Number Labels
  x-api-slug: github
  description: List labels on an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels
  tags: Repos, Owner, Repo, Issues, Number, Labels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberlabels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberlabels-get-openapi.md
- name: Github Add Repos Owner Repo Issues Number Labels
  x-api-slug: github
  description: Add labels to an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels
  tags: Repos, Owner, Repo, Issues, Number, Labels
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberlabels-post-openapi.md
- name: Github Put Repos Owner Repo Issues Number Labels
  x-api-slug: github
  description: |-
    Replace all labels for an issue.
    Sending an empty array ([]) will remove all Labels from the Issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels
  tags: Repos, Owner, Repo, Issues, Number, Labels
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberlabels-put-openapi.md
- name: Github Delete Repos Owner Repo Issues Number Labels Name
  x-api-slug: github
  description: Remove a label from an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels/{name}
  tags: Repos, Owner, Repo, Issues, Number, Labels, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberlabelsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoissuesnumberlabelsname-delete-openapi.md
- name: Github Get Repos Owner Repo Keys
  x-api-slug: github
  description: Get list of keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/keys
  tags: Repos, Owner, Repo, Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepokeys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepokeys-get-openapi.md
- name: Github Add Repos Owner Repo Keys
  x-api-slug: github
  description: Create a key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/keys
  tags: Repos, Owner, Repo, Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepokeys-post-openapi.md
- name: Github Delete Repos Owner Repo Keys Key
  x-api-slug: github
  description: Delete a key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/keys/{keyId}
  tags: Repos, Owner, Repo, Keys, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepokeyskeyid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepokeyskeyid-delete-openapi.md
- name: Github Get Repos Owner Repo Keys Key
  x-api-slug: github
  description: Get a key
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/keys/{keyId}
  tags: Repos, Owner, Repo, Keys, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepokeyskeyid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepokeyskeyid-get-openapi.md
- name: Github Get Repos Owner Repo Labels
  x-api-slug: github
  description: List all labels for this repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/labels
  tags: Repos, Owner, Repo, Labels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolabels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolabels-get-openapi.md
- name: Github Add Repos Owner Repo Labels
  x-api-slug: github
  description: Create a label.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/labels
  tags: Repos, Owner, Repo, Labels
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolabels-post-openapi.md
- name: Github Delete Repos Owner Repo Labels Name
  x-api-slug: github
  description: Delete a label.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/labels/{name}
  tags: Repos, Owner, Repo, Labels, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolabelsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolabelsname-delete-openapi.md
- name: Github Get Repos Owner Repo Labels Name
  x-api-slug: github
  description: Get a single label.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/labels/{name}
  tags: Repos, Owner, Repo, Labels, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolabelsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolabelsname-get-openapi.md
- name: Github Patch Repos Owner Repo Labels Name
  x-api-slug: github
  description: Update a label.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/labels/{name}
  tags: Repos, Owner, Repo, Labels, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolabelsname-patch-openapi.md
- name: Github Get Repos Owner Repo Languages
  x-api-slug: github
  description: |-
    List languages.
    List languages for the specified repository. The value on the right of a
    language is the number of bytes of code written in that language.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/languages
  tags: Repos, Owner, Repo, Languages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolanguages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepolanguages-get-openapi.md
- name: Github Add Repos Owner Repo Merges
  x-api-slug: github
  description: Perform a merge.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/merges
  tags: Repos, Owner, Repo, Merges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomerges-post-openapi.md
- name: Github Get Repos Owner Repo Milestones
  x-api-slug: github
  description: List milestones for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/milestones
  tags: Repos, Owner, Repo, Milestones
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestones-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestones-get-openapi.md
- name: Github Add Repos Owner Repo Milestones
  x-api-slug: github
  description: Create a milestone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/milestones
  tags: Repos, Owner, Repo, Milestones
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestones-post-openapi.md
- name: Github Delete Repos Owner Repo Milestones Number
  x-api-slug: github
  description: Delete a milestone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/milestones/{number}
  tags: Repos, Owner, Repo, Milestones, Number
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestonesnumber-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestonesnumber-delete-openapi.md
- name: Github Get Repos Owner Repo Milestones Number
  x-api-slug: github
  description: Get a single milestone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/milestones/{number}
  tags: Repos, Owner, Repo, Milestones, Number
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestonesnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestonesnumber-get-openapi.md
- name: Github Patch Repos Owner Repo Milestones Number
  x-api-slug: github
  description: Update a milestone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/milestones/{number}
  tags: Repos, Owner, Repo, Milestones, Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestonesnumber-patch-openapi.md
- name: Github Get Repos Owner Repo Milestones Number Labels
  x-api-slug: github
  description: Get labels for every issue in a milestone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/milestones/{number}/labels
  tags: Repos, Owner, Repo, Milestones, Number, Labels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestonesnumberlabels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepomilestonesnumberlabels-get-openapi.md
- name: Github Get Repos Owner Repo Notifications
  x-api-slug: github
  description: |-
    List your notifications in a repository
    List all notifications for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/notifications
  tags: Repos, Owner, Repo, Notifications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreponotifications-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreponotifications-get-openapi.md
- name: Github Put Repos Owner Repo Notifications
  x-api-slug: github
  description: |-
    Mark notifications as read in a repository.
    Marking all notifications in a repository as "read" removes them from the
    default view on GitHub.com.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/notifications
  tags: Repos, Owner, Repo, Notifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreponotifications-put-openapi.md
- name: Github Get Repos Owner Repo Pulls
  x-api-slug: github
  description: List pull requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls
  tags: Repos, Owner, Repo, Pulls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopulls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopulls-get-openapi.md
- name: Github Add Repos Owner Repo Pulls
  x-api-slug: github
  description: Create a pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls
  tags: Repos, Owner, Repo, Pulls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopulls-post-openapi.md
- name: Github Get Repos Owner Repo Pulls Comments
  x-api-slug: github
  description: |-
    List comments in a repository.
    By default, Review Comments are ordered by ascending ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments
  tags: Repos, Owner, Repo, Pulls, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullscomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullscomments-get-openapi.md
- name: Github Delete Repos Owner Repo Pulls Comments Comment
  x-api-slug: github
  description: Delete a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments/{commentId}
  tags: Repos, Owner, Repo, Pulls, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullscommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullscommentscommentid-delete-openapi.md
- name: Github Get Repos Owner Repo Pulls Comments Comment
  x-api-slug: github
  description: Get a single comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments/{commentId}
  tags: Repos, Owner, Repo, Pulls, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullscommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullscommentscommentid-get-openapi.md
- name: Github Patch Repos Owner Repo Pulls Comments Comment
  x-api-slug: github
  description: Edit a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments/{commentId}
  tags: Repos, Owner, Repo, Pulls, Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullscommentscommentid-patch-openapi.md
- name: Github Get Repos Owner Repo Pulls Number
  x-api-slug: github
  description: Get a single pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}
  tags: Repos, Owner, Repo, Pulls, Number
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumber-get-openapi.md
- name: Github Patch Repos Owner Repo Pulls Number
  x-api-slug: github
  description: Update a pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}
  tags: Repos, Owner, Repo, Pulls, Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumber-patch-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Comments
  x-api-slug: github
  description: List comments on a pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/comments
  tags: Repos, Owner, Repo, Pulls, Number, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumbercomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumbercomments-get-openapi.md
- name: Github Add Repos Owner Repo Pulls Number Comments
  x-api-slug: github
  description: |-
    Create a comment.
      #TODO Alternative input ( http://developer.github.com/v3/pulls/comments/ )
      description: |
        Alternative Input.
        Instead of passing commit_id, path, and position you can reply to an
        existing Pull Request Comment like this:

            body
               Required string
            in_reply_to
               Required number - Comment id to reply to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/comments
  tags: Repos, Owner, Repo, Pulls, Number, Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumbercomments-post-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Commits
  x-api-slug: github
  description: List commits on a pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/commits
  tags: Repos, Owner, Repo, Pulls, Number, Commits
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumbercommits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumbercommits-get-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Files
  x-api-slug: github
  description: List pull requests files.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/files
  tags: Repos, Owner, Repo, Pulls, Number, Files
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumberfiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumberfiles-get-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Merge
  x-api-slug: github
  description: Get if a pull request has been merged.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/merge
  tags: Repos, Owner, Repo, Pulls, Number, Merge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumbermerge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumbermerge-get-openapi.md
- name: Github Put Repos Owner Repo Pulls Number Merge
  x-api-slug: github
  description: Merge a pull request (Merge Button's)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/merge
  tags: Repos, Owner, Repo, Pulls, Number, Merge
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepopullsnumbermerge-put-openapi.md
- name: Github Get Repos Owner Repo Readme
  x-api-slug: github
  description: |-
    Get the README.
    This method returns the preferred README for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/readme
  tags: Repos, Owner, Repo, Readme
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeadme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeadme-get-openapi.md
- name: Github Get Repos Owner Repo Releases
  x-api-slug: github
  description: Users with push access to the repository will receive all releases
    (i.e., published releases and draft releases). Users with pull access will receive
    published releases only
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/releases
  tags: Repos, Owner, Repo, Releases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleases-get-openapi.md
- name: Github Add Repos Owner Repo Releases
  x-api-slug: github
  description: |-
    Create a release
    Users with push access to the repository can create a release.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/releases
  tags: Repos, Owner, Repo, Releases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleases-post-openapi.md
- name: Github Delete Repos Owner Repo Releases Assets
  x-api-slug: github
  description: Delete a release asset
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/releases/assets/{id}
  tags: Repos, Owner, Repo, Releases, Assets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesassetsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesassetsid-delete-openapi.md
- name: Github Get Repos Owner Repo Releases Assets
  x-api-slug: github
  description: Get a single release asset
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/releases/assets/{id}
  tags: Repos, Owner, Repo, Releases, Assets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesassetsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesassetsid-get-openapi.md
- name: Github Patch Repos Owner Repo Releases Assets
  x-api-slug: github
  description: |-
    Edit a release asset
    Users with push access to the repository can edit a release asset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/releases/assets/{id}
  tags: Repos, Owner, Repo, Releases, Assets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesassetsid-patch-openapi.md
- name: Github Delete Repos Owner Repo Releases
  x-api-slug: github
  description: Users with push access to the repository can delete a release.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/releases/{id}
  tags: Repos, Owner, Repo, Releases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesid-delete-openapi.md
- name: Github Get Repos Owner Repo Releases
  x-api-slug: github
  description: Get a single release
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/releases/{id}
  tags: Repos, Owner, Repo, Releases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesid-get-openapi.md
- name: Github Patch Repos Owner Repo Releases
  x-api-slug: github
  description: Users with push access to the repository can edit a release
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/releases/{id}
  tags: Repos, Owner, Repo, Releases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesid-patch-openapi.md
- name: Github Get Repos Owner Repo Releases  Assets
  x-api-slug: github
  description: List assets for a release
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/releases/{id}/assets
  tags: Repos, Owner, Repo, Releases, , Assets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesidassets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreporeleasesidassets-get-openapi.md
- name: Github Get Repos Owner Repo Stargazers
  x-api-slug: github
  description: List Stargazers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/stargazers
  tags: Repos, Owner, Repo, Stargazers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostargazers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostargazers-get-openapi.md
- name: Github Get Repos Owner Repo Stats Code Frequency
  x-api-slug: github
  description: |-
    Get the number of additions and deletions per week.
    Returns a weekly aggregate of the number of additions and deletions pushed
    to a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/stats/code_frequency
  tags: Repos, Owner, Repo, Stats, Code, Frequency,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatscode-frequency-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatscode-frequency-get-openapi.md
- name: Github Get Repos Owner Repo Stats Commit Activity
  x-api-slug: github
  description: |-
    Get the last year of commit activity data.
    Returns the last year of commit activity grouped by week. The days array
    is a group of commits per day, starting on Sunday.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/stats/commit_activity
  tags: Repos, Owner, Repo, Stats, Commit, Activity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatscommit-activity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatscommit-activity-get-openapi.md
- name: Github Get Repos Owner Repo Stats Contributors
  x-api-slug: github
  description: Get contributors list with additions, deletions, and commit counts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/stats/contributors
  tags: Repos, Owner, Repo, Stats, Contributors
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatscontributors-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatscontributors-get-openapi.md
- name: Github Get Repos Owner Repo Stats Participation
  x-api-slug: github
  description: Get the weekly commit count for the repo owner and everyone else.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/stats/participation
  tags: Repos, Owner, Repo, Stats, Participation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatsparticipation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatsparticipation-get-openapi.md
- name: Github Get Repos Owner Repo Stats Punch Card
  x-api-slug: github
  description: |-
    Get the number of commits per hour in each day.
    Each array contains the day number, hour number, and number of commits
    0-6 Sunday - Saturday
    0-23 Hour of day
    Number of commits

    For example, [2, 14, 25] indicates that there were 25 total commits, during
    the 2.00pm hour on Tuesdays. All times are based on the time zone of
    individual commits.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/stats/punch_card
  tags: Repos, Owner, Repo, Stats, Punch, Card
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatspunch-card-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatspunch-card-get-openapi.md
- name: Github Get Repos Owner Repo Statuses Ref
  x-api-slug: github
  description: List Statuses for a specific Ref.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/statuses/{ref}
  tags: Repos, Owner, Repo, Statuses, Ref
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatusesref-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatusesref-get-openapi.md
- name: Github Add Repos Owner Repo Statuses Ref
  x-api-slug: github
  description: Create a Status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/statuses/{ref}
  tags: Repos, Owner, Repo, Statuses, Ref
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepostatusesref-post-openapi.md
- name: Github Get Repos Owner Repo Subscribers
  x-api-slug: github
  description: List watchers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/subscribers
  tags: Repos, Owner, Repo, Subscribers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreposubscribers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreposubscribers-get-openapi.md
- name: Github Delete Repos Owner Repo Subscription
  x-api-slug: github
  description: Delete a Repository Subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/subscription
  tags: Repos, Owner, Repo, Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreposubscription-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreposubscription-delete-openapi.md
- name: Github Get Repos Owner Repo Subscription
  x-api-slug: github
  description: Get a Repository Subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/subscription
  tags: Repos, Owner, Repo, Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreposubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreposubscription-get-openapi.md
- name: Github Put Repos Owner Repo Subscription
  x-api-slug: github
  description: Set a Repository Subscription
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/subscription
  tags: Repos, Owner, Repo, Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerreposubscription-put-openapi.md
- name: Github Get Repos Owner Repo Tags
  x-api-slug: github
  description: Get list of tags.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/tags
  tags: Repos, Owner, Repo, Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepotags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepotags-get-openapi.md
- name: Github Get Repos Owner Repo Teams
  x-api-slug: github
  description: Get list of teams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/teams
  tags: Repos, Owner, Repo, Teams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoteams-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoteams-get-openapi.md
- name: Github Get Repos Owner Repo Watchers
  x-api-slug: github
  description: List Stargazers. New implementation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/watchers
  tags: Repos, Owner, Repo, Watchers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepowatchers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepowatchers-get-openapi.md
- name: Github Get Repos Owner Repo Archive Format Path
  x-api-slug: github
  description: |-
    Get archive link.
    This method will return a 302 to a URL to download a tarball or zipball
    archive for a repository. Please make sure your HTTP framework is
    configured to follow redirects or you will need to use the Location header
    to make a second GET request.
    Note: For private repositories, these links are temporary and expire quickly.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/{archive_format}/{path}
  tags: Repos, Owner, Repo, Archives, Format, Path
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoarchive-formatpath-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/reposownerrepoarchive-formatpath-get-openapi.md
- name: Github Get Repositories
  x-api-slug: github
  description: |-
    List all public repositories.
    This provides a dump of every public repository, in the order that they
    were created.
    Note: Pagination is powered exclusively by the since parameter. is the
    Link header to get the URL for the next page of repositories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repositories
  tags: Repositories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/repositories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/repositories-get-openapi.md
- name: Github Get Search Code
  x-api-slug: github
  description: Search code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////search/code
  tags: Search, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/searchcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/searchcode-get-openapi.md
- name: Github Get Search Issues
  x-api-slug: github
  description: Find issues by state and keyword. (This method returns up to 100 results
    per page.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////search/issues
  tags: Search, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/searchissues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/searchissues-get-openapi.md
- name: Github Get Search Repositories
  x-api-slug: github
  description: Search repositories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////search/repositories
  tags: Search, Repositories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/searchrepositories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/searchrepositories-get-openapi.md
- name: Github Get Search Users
  x-api-slug: github
  description: Search users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////search/users
  tags: Search, Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/searchusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/searchusers-get-openapi.md
- name: Github Delete Teams Team
  x-api-slug: github
  description: |-
    Delete team.
    In order to delete a team, the authenticated user must be an owner of the
    org that the team is associated with.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}
  tags: Teams, Team
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamid-delete-openapi.md
- name: Github Get Teams Team
  x-api-slug: github
  description: Get team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}
  tags: Teams, Team
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamid-get-openapi.md
- name: Github Patch Teams Team
  x-api-slug: github
  description: |-
    Edit team.
    In order to edit a team, the authenticated user must be an owner of the org
    that the team is associated with.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}
  tags: Teams, Team
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamid-patch-openapi.md
- name: Github Get Teams Team Members
  x-api-slug: github
  description: |-
    List team members.
    In order to list members in a team, the authenticated user must be a member
    of the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/members
  tags: Teams, Team, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembers-get-openapi.md
- name: Github Delete Teams Team Members Username
  x-api-slug: github
  description: |-
    The "Remove team member" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Remove team membership API instead. It allows you to remove both active and pending memberships.

    Remove team member.
    In order to remove a user from a team, the authenticated user must have 'admin'
    permissions to the team or be an owner of the org that the team is associated
    with.
    NOTE This does not delete the user, it just remove them from the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/members/{username}
  tags: Teams, Team, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembersusername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembersusername-delete-openapi.md
- name: Github Get Teams Team Members Username
  x-api-slug: github
  description: |-
    The "Get team member" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Get team membership API instead. It allows you to get both active and pending memberships.

    Get team member.
    In order to get if a user is a member of a team, the authenticated user mus
    be a member of the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/members/{username}
  tags: Teams, Team, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembersusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembersusername-get-openapi.md
- name: Github Put Teams Team Members Username
  x-api-slug: github
  description: |-
    The API (described below) is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Add team membership API instead. It allows you to invite new organization members to your teams.

    Add team member.
    In order to add a user to a team, the authenticated user must have 'admin'
    permissions to the team or be an owner of the org that the team is associated
    with.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/members/{username}
  tags: Teams, Team, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembersusername-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembersusername-put-openapi.md
- name: Github Delete Teams Team Memberships Username
  x-api-slug: github
  description: |-
    Remove team membership.
    In order to remove a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with. NOTE: This does not delete the user, it just removes their membership from the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/memberships/{username}
  tags: Teams, Team, Memberships, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembershipsusername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembershipsusername-delete-openapi.md
- name: Github Get Teams Team Memberships Username
  x-api-slug: github
  description: |-
    Get team membership.
    In order to get a user's membership with a team, the authenticated user must be a member of the team or an owner of the team's organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/memberships/{username}
  tags: Teams, Team, Memberships, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembershipsusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembershipsusername-get-openapi.md
- name: Github Put Teams Team Memberships Username
  x-api-slug: github
  description: |-
    Add team membership.
    In order to add a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with.

    If the user is already a part of the team's organization (meaning they're on at least one other team in the organization), this endpoint will add the user to the team.

    If the user is completely unaffiliated with the team's organization (meaning they're on none of the organization's teams), this endpoint will send an invitation to the user via email. This newly-created membership will be in the 'pending' state until the user accepts the invitation, at which point the membership will transition to the 'active' state and the user will be added as a member of the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/memberships/{username}
  tags: Teams, Team, Memberships, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembershipsusername-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidmembershipsusername-put-openapi.md
- name: Github Get Teams Team Repos
  x-api-slug: github
  description: List team repos
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/repos
  tags: Teams, Team, Repos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidrepos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidrepos-get-openapi.md
- name: Github Put Teams Team Repos Org Repo
  x-api-slug: github
  description: In order to add a repository to a team, the authenticated user must
    be an owner of the org that the team is associated with. Also, the repository
    must be owned by the organization, or a direct fork of a repository owned by the
    organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/repos/{org}/{repo}
  tags: Teams, Team, Repos, Org, Repo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidreposorgrepo-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidreposorgrepo-put-openapi.md
- name: Github Delete Teams Team Repos Owner Repo
  x-api-slug: github
  description: 'In order to remove a repository from a team, the authenticated user
    must be an owner of the org that the team is associated with. NOTE: This does
    not delete the repository, it just removes it from the team.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/repos/{owner}/{repo}
  tags: Teams, Team, Repos, Owner, Repo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidreposownerrepo-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidreposownerrepo-delete-openapi.md
- name: Github Get Teams Team Repos Owner Repo
  x-api-slug: github
  description: Check if a team manages a repository
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/repos/{owner}/{repo}
  tags: Teams, Team, Repos, Owner, Repo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidreposownerrepo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/teamsteamidreposownerrepo-get-openapi.md
- name: Github Get User
  x-api-slug: github
  description: Get the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/user-get-openapi.md
- name: Github Patch User
  x-api-slug: github
  description: Update the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/user-patch-openapi.md
- name: Github Delete User Emails
  x-api-slug: github
  description: |-
    Delete email address(es).
    You can include a single email address or an array of addresses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/emails
  tags: User, Emails
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/useremails-delete-openapi.md
- name: Github Get User Emails
  x-api-slug: github
  description: |-
    List email addresses for a user.
    In the final version of the API, this method will return an array of hashes
    with extended information for each email address indicating if the address
    has been verified and if it's primary email address for GitHub.
    Until API v3 is finalized, use the application/vnd.github.v3 media type to
    get other response format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/emails
  tags: User, Emails
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/useremails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/useremails-get-openapi.md
- name: Github Add User Emails
  x-api-slug: github
  description: |-
    Add email address(es).
    You can post a single email address or an array of addresses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/emails
  tags: User, Emails
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/useremails-post-openapi.md
- name: Github Get User Followers
  x-api-slug: github
  description: List the authenticated user's followers
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/followers
  tags: User, Followers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userfollowers-get-openapi.md
- name: Github Get User Following
  x-api-slug: github
  description: List who the authenticated user is following.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/following
  tags: User, Following
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userfollowing-get-openapi.md
- name: Github Delete User Following Username
  x-api-slug: github
  description: |-
    Unfollow a user.
    Unfollowing a user requires the user to be logged in and authenticated with
    basic auth or OAuth with the user:follow scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/following/{username}
  tags: User, Following, Username
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userfollowingusername-delete-openapi.md
- name: Github Get User Following Username
  x-api-slug: github
  description: Check if you are following a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/following/{username}
  tags: User, Following, Username
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userfollowingusername-get-openapi.md
- name: Github Put User Following Username
  x-api-slug: github
  description: |-
    Follow a user.
    Following a user requires the user to be logged in and authenticated with
    basic auth or OAuth with the user:follow scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/following/{username}
  tags: User, Following, Username
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userfollowingusername-put-openapi.md
- name: Github Get User Issues
  x-api-slug: github
  description: |-
    List issues.
    List all issues across owned and member repositories for the authenticated
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/issues
  tags: User, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userissues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userissues-get-openapi.md
- name: Github Get User Keys
  x-api-slug: github
  description: |-
    List your public keys.
    Lists the current user's keys. Management of public keys via the API requires
    that you are authenticated through basic auth, or OAuth with the 'user', 'write:public_key' scopes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/keys
  tags: User, Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userkeys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userkeys-get-openapi.md
- name: Github Add User Keys
  x-api-slug: github
  description: Create a public key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/keys
  tags: User, Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userkeys-post-openapi.md
- name: Github Delete User Keys Key
  x-api-slug: github
  description: Delete a public key. Removes a public key. Requires that you are authenticated
    via Basic Auth or via OAuth with at least admin:public_key scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/keys/{keyId}
  tags: User, Keys, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userkeyskeyid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userkeyskeyid-delete-openapi.md
- name: Github Get User Keys Key
  x-api-slug: github
  description: Get a single public key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/keys/{keyId}
  tags: User, Keys, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userkeyskeyid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userkeyskeyid-get-openapi.md
- name: Github Get User Orgs
  x-api-slug: github
  description: List public and private organizations for the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/orgs
  tags: User, Orgs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userorgs-get-openapi.md
- name: Github Get User Repos
  x-api-slug: github
  description: |-
    List repositories for the authenticated user. Note that this does not include
    repositories owned by organizations which the user can access. You can lis
    user organizations and list organization repositories separately.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/repos
  tags: User, Repos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userrepos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userrepos-get-openapi.md
- name: Github Add User Repos
  x-api-slug: github
  description: |-
    Create a new repository for the authenticated user. OAuth users must supply
    repo scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/repos
  tags: User, Repos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userrepos-post-openapi.md
- name: Github Get User Starred
  x-api-slug: github
  description: List repositories being starred by the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/starred
  tags: User, Starred
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userstarred-get-openapi.md
- name: Github Delete User Starred Owner Repo
  x-api-slug: github
  description: Unstar a repository
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/starred/{owner}/{repo}
  tags: User, Starred, Owner, Repo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userstarredownerrepo-delete-openapi.md
- name: Github Get User Starred Owner Repo
  x-api-slug: github
  description: Check if you are starring a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/starred/{owner}/{repo}
  tags: User, Starred, Owner, Repo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userstarredownerrepo-get-openapi.md
- name: Github Put User Starred Owner Repo
  x-api-slug: github
  description: Star a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/starred/{owner}/{repo}
  tags: User, Starred, Owner, Repo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userstarredownerrepo-put-openapi.md
- name: Github Get User Subscriptions
  x-api-slug: github
  description: List repositories being watched by the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/subscriptions
  tags: User, Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersubscriptions-get-openapi.md
- name: Github Delete User Subscriptions Owner Repo
  x-api-slug: github
  description: Stop watching a repository
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/subscriptions/{owner}/{repo}
  tags: User, Subscriptions, Owner, Repo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersubscriptionsownerrepo-delete-openapi.md
- name: Github Get User Subscriptions Owner Repo
  x-api-slug: github
  description: Check if you are watching a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/subscriptions/{owner}/{repo}
  tags: User, Subscriptions, Owner, Repo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersubscriptionsownerrepo-get-openapi.md
- name: Github Put User Subscriptions Owner Repo
  x-api-slug: github
  description: Watch a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/subscriptions/{owner}/{repo}
  tags: User, Subscriptions, Owner, Repo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersubscriptionsownerrepo-put-openapi.md
- name: Github Get User Teams
  x-api-slug: github
  description: List all of the teams across all of the organizations to which the
    authenticated user belongs. This method requires user or repo scope when authenticating
    via OAuth.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/teams
  tags: User, Teams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userteams-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/userteams-get-openapi.md
- name: Github Get Users
  x-api-slug: github
  description: |-
    Get all users.
    This provides a dump of every user, in the order that they signed up for GitHub.
    Note: Pagination is powered exclusively by the since parameter. Use the Link
    header to get the URL for the next page of users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/users-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/users-get-openapi.md
- name: Github Get Users Username
  x-api-slug: github
  description: Get a single user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}
  tags: Users, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusername-get-openapi.md
- name: Github Get Users Username Events
  x-api-slug: github
  description: If you are authenticated as the given user, you will see your private
    events. Otherwise, you'll only see public events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/events
  tags: Users, Username, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernameevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernameevents-get-openapi.md
- name: Github Get Users Username Events Orgs Org
  x-api-slug: github
  description: This is the user's organization dashboard. You must be authenticated
    as the user to view this.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/events/orgs/{org}
  tags: Users, Username, Events, Orgs, Org
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernameeventsorgsorg-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernameeventsorgsorg-get-openapi.md
- name: Github Get Users Username Followers
  x-api-slug: github
  description: List a user's followers
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/followers
  tags: Users, Username, Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamefollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamefollowers-get-openapi.md
- name: Github Get Users Username Following Targetuser
  x-api-slug: github
  description: Check if one user follows another.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/following/{targetUser}
  tags: Users, Username, Following, Targetuser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamefollowingtargetuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamefollowingtargetuser-get-openapi.md
- name: Github Get Users Username Gists
  x-api-slug: github
  description: List a users gists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/gists
  tags: Users, Username, Gists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamegists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamegists-get-openapi.md
- name: Github Get Users Username Keys
  x-api-slug: github
  description: |-
    List public keys for a user.
    Lists the verified public keys for a user. This is accessible by anyone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/keys
  tags: Users, Username, Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamekeys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamekeys-get-openapi.md
- name: Github Get Users Username Orgs
  x-api-slug: github
  description: List all public organizations for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/orgs
  tags: Users, Username, Orgs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernameorgs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernameorgs-get-openapi.md
- name: Github Get Users Username Received Events
  x-api-slug: github
  description: These are events that you'll only see public events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/received_events
  tags: Users, Username, Received, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamereceived-events-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamereceived-events-get-openapi.md
- name: Github Get Users Username Received Events Public
  x-api-slug: github
  description: List public events that a user has received
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/received_events/public
  tags: Users, Username, Received, Events, Public
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamereceived-eventspublic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamereceived-eventspublic-get-openapi.md
- name: Github Get Users Username Repos
  x-api-slug: github
  description: List public repositories for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/repos
  tags: Users, Username, Repos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamerepos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamerepos-get-openapi.md
- name: Github Get Users Username Starred
  x-api-slug: github
  description: List repositories being starred by a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/starred
  tags: Users, Username, Starred
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamestarred-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamestarred-get-openapi.md
- name: Github Get Users Username Subscriptions
  x-api-slug: github
  description: List repositories being watched by a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/subscriptions
  tags: Users, Username, Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamesubscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/usersusernamesubscriptions-get-openapi.md
- name: Github Get Organizations
  x-api-slug: github
  description: Get all organizations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////organizations
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/organizations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/organizations-get-openapi.md
- name: Github
  x-api-slug: github
  description: With a community of more than 10 million people, developers can discover,
    use and contribute to over 24 million projects using a powerful, collaborative
    workflow.    Whether using GitHub.com or your own instance of GitHub Enterprise,
    you can integrate ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: GitHub
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/github/master/_listings/github/openapi.md
x-common:
- type: x-net-library
  url: https://github.com/octokit/octokit.net
- type: x-base
  url: https://api.github.com
- type: x-blog
  url: http://github.com/blog
- type: x-blog-rss
  url: https://github.com/blog/subscribe
- type: x-change-log
  url: https://developer.github.com/changes/
- type: x-contact-form
  url: https://github.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/github
- type: x-crunchbase
  url: https://crunchbase.com/organization/github
- type: x-developer
  url: https://developer.github.com/
- type: x-github
  url: https://github.com/github
- type: x-guides
  url: https://developer.github.com/guides/
- type: x-ios-sdk
  url: https://github.com/octokit/octokit.objc
- type: x-pricing
  url: https://github.com/pricing
- type: x-privacy
  url: http://help.github.com/privacy-policy/
- type: x-ruby-library
  url: https://github.com/octokit/octokit.rb
- type: x-security
  url: http://help.github.com/security/
- type: x-status
  url: https://status.github.com/
- type: x-terms-of-service
  url: http://help.github.com/terms-of-service/
- type: x-transparency-report
  url: https://github.com/blog/1987-github-s-2014-transparency-report
- type: x-twitter
  url: https://twitter.com/github
- type: x-webhooks
  url: https://developer.github.com/webhooks/
- type: x-website
  url: https://github.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
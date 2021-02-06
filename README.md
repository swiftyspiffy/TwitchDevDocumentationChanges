# TwitchDevDocumentationChanges!
Automatically see changes to https://dev.twitch.tv/docs/api/reference . Currently only supports Helix api documentation.

This repo has two components:
- current_schema.json: Represents the current state of the documentation. See diffs to this file for changes made to the documentation.
- history directory: Every day a new schema will be pushed to this directory. The name of the file will be the date it was scraped and pushed.

Currently supported documentation components:
- Title
- Authentication
- Pagination support (reverse, forward)
- Url (method, url)
- Required query parameters
- Required body parameters
- Optional query parameters
- Response fields


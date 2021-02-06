# dev.twitch.tv Documentation Change Detection
Automatically see changes to https://dev.twitch.tv/docs/api/reference . Currently only supports Helix api documentation.

This repo has two components:
- current_schema.json: Represents the current state of the documentation. See diffs to this file for changes made to the documentation.
- history directory: Every day a new schema will be pushed to this directory. The name of the file will be the date it was scraped and pushed.

Currently supported documentation components:
- Title
- Authentication (scope)
- Pagination support (reverse, forward)
- Url (method, url)
- Required query parameters (parameter, type, description)
- Required body parameters (parameter, type, description)
- Optional query parameters (parameter, type, description)
- Response fields (parameter, type, description)


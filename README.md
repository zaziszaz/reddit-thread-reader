# reddit-thread-reader

A personal, read-only tool for reading Reddit threads that its owner chooses.

## What it does

When the owner pastes a link to a Reddit thread, the tool fetches that one thread (the post and its full comment tree) through Reddit's official OAuth API (oauth.reddit.com), using application-only authentication. It saves the thread as a markdown file on the owner's own computer, for personal reading and note-taking. It is used from the owner's own AI coding assistant.

## How it is used

- On demand only: nothing runs unless the owner pastes a thread link.
- A few threads a day, well within Reddit's published rate limits.
- Every request sends a descriptive User-Agent that identifies the tool.

## What it never does

- It never posts, comments, votes, or sends messages.
- It never moderates anything.
- It never crawls Reddit in bulk.
- It never resells or redistributes Reddit content.
- It never uses Reddit content to train AI models.
- It has no commercial use.

## Status

Code will be published here once the reader is built; this repository will contain only the reader, with no credentials.

## License

MIT, see LICENSE.

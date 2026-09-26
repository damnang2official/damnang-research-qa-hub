# Damnang Research Q&A feeds

Public JSON for ChatGPT / map sites. Public questions and optional short answer previews. Full answers stay on Substack.

## Raw URLs
- Threads (questions): https://raw.githubusercontent.com/damnang2official/damnang-research-qa-hub/main/public/threads-questions.json
- Curated Q&A: https://raw.githubusercontent.com/damnang2official/damnang-research-qa-hub/main/public/qa.json

Fetch with cache: 'no-store'. Do not host answer bodies here.

## Optional answer previews

`threads-questions.json` may include `answer_teaser` on an answered item with a valid `paid_url`. Use a manually reviewed plain-text excerpt from the actual reply, no more than 160 characters. Preserve the meaning and qualifiers; an ellipsis can mark omitted continuation. Do not publish full answer bodies, HTML, or guessed answers. When regenerating the feed, preserve reviewed previews by item ID while the underlying answer is unchanged; otherwise review or remove them.

The map fetches this field with the questions on each page load and displays it under “From the answer”. Missing or oversized previews are not displayed. Edit the JSON to update a preview without redeploying the map. GitHub CDN propagation can take a few minutes.

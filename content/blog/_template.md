---
title: "Your Post Title Here"
date: 2026-05-01T10:00:00+03:00
image: "images/blog/your-image.jpg"
author: "Name"
tags: ["announcement"]
categories: ["News"]
description: "A short one-line summary that appears in the RSS feed and search results."
draft: true
---

Write your post content here using regular Markdown.

You can use **bold**, *italic*, [links](https://example.com), images, and all
standard Markdown formatting.

## Tips for writing posts

- Keep the `date` in ISO 8601 format with the Bucharest timezone offset (+03:00)
- The `image` field is optional — if provided, it appears in the RSS feed as an enclosure
- Set `draft: true` while working on a post, then change to `false` when ready to publish
- Use descriptive `tags` — they become RSS `<category>` elements and help with filtering
- The filename should follow the pattern `YYYY-MM-DD-short-slug.md` (e.g. `2026-05-01-cfp-open.md`)
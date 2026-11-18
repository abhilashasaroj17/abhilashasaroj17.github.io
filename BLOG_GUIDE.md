# Blog publishing guide

The blog is available at https://abhilashasaroj17.github.io/blog/.

Posts are GitHub Pages / Jekyll Markdown files. To publish a new post, create a file in `_posts/` with the filename `YYYY-MM-DD-short-title.md`. The blog list updates automatically, newest first.

Example:

```markdown
---
layout: post
title: "An example title"
date: 2026-11-18
description: "A one-sentence summary of the post."
category: "Research update"
---

Write the post in Markdown here, with paragraphs and headings.
```

To edit or remove a post, edit or delete its Markdown file. Changes to the main branch trigger GitHub Pages deployment automatically.

When asking ChatGPT to publish, provide the topic or draft and state whether to publish immediately. It can prepare the Markdown, commit it to the connected repository, and verify the deployment.

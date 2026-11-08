# Tiansheng Zhang's personal website

Academic homepage, engineering portfolio, and Markdown technical blog for https://tszhang87.github.io.

## Publish

Under **Settings → Pages**, choose **Deploy from a branch**, then **main** and **/ (root)**. Save. Inspect the Pages workflow under Actions if a build fails.

## Write a post

Create `_posts/YYYY-MM-DD-your-title.md` using the actual publication date:

```markdown
---
layout: post
title: "Your article title"
description: "A short summary."
category: Distributed systems
---

Your article in Markdown.
```

Commit to main. The Writing archive updates automatically. `_drafts/first-post.md` is a starter, excluded from the rendered site. Draft source is still visible in this public repository. Do not commit confidential material.

## Edit

- `index.html`: biography, research, engineering interests.
- `_config.yml`: site title, URL, description.
- `assets/css/style.css`: responsive design.
- `_layouts/post.html`: article layout.

The CacheKindle entry awaits a verified full author list and direct paper link. Research links include Google Scholar and a BU-hosted paper. No email or CV has been invented.

## Local preview (Ruby required)

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000. Add `--drafts` to preview drafts locally.

# No Scroll / 别刷了

Energy is valuable. Only read what matters to you as I don't want to read too much information every day.An experimental front-end concept that turns the public [`follow-builders`](https://github.com/zarazhangrui/follow-builders) feed into a pixel-style daily AI digest.

## Credit First

This project is **inspired by and built on top of** the public feed and workflow ideas from [`zarazhangrui/follow-builders`](https://github.com/zarazhangrui/follow-builders).

Special thanks to **Zara Zhang (`zarazhangrui`)** for:

- the product inspiration
- the public feed structure
- the upstream GitHub Actions / centralized content pipeline idea
- the curation and maintenance work behind the upstream feed

This repo does **not** claim ownership of the upstream source content, upstream feed infrastructure, or upstream curation work.

## Feed Source

This project consumes the public feed published from the upstream repository:

- [https://github.com/zarazhangrui/follow-builders](https://github.com/zarazhangrui/follow-builders)

The upstream discussion and issue entry is here:

- [https://github.com/zarazhangrui/follow-builders/issues](https://github.com/zarazhangrui/follow-builders/issues)

All source-list changes, feed requests, or upstream content questions should be treated as upstream matters first.

## What This Project Is

`No Scroll / 别刷了` is a lightweight UI experiment:

- reads public feed data from `follow-builders`
- does not require product-side API keys
- keeps the original retro game-like interface
- tries to make daily builder updates faster to browse
- filters low-signal social posts before they become cards
- supports X posts, podcasts, and blogs when available in the upstream feed

## What This Project Is Not

- not the owner of the upstream content
- not the owner of the `follow-builders` feed
- not a replacement for the original source links
- not a replacement for the upstream repository or upstream issues page
- not a Chinese translation engine for all upstream content

When the upstream feed does not provide Chinese fields, this project keeps the original text and only localizes the surrounding UI and interaction copy.

## Data Source

All content is based on the public files exposed by the upstream project, including feeds such as:

- `feed-x.json`
- `feed-podcasts.json`
- `feed-blogs.json`

Upstream repository:

- [https://github.com/zarazhangrui/follow-builders](https://github.com/zarazhangrui/follow-builders)

Upstream issues:

- [https://github.com/zarazhangrui/follow-builders/issues](https://github.com/zarazhangrui/follow-builders/issues)

This project only consumes the publicly exposed feed and does not replace the upstream maintainer's decisions, repository, or issue tracker.

## Current Product Logic

The current front-end logic focuses on:

- pulling the latest feed on launch
- ranking and selecting a readable Top 5
- avoiding low-information posts
- avoiding the same builder dominating the whole list
- surfacing original links early so users can open the source immediately
- making quiz copy feel user-facing instead of system-facing
- making podcast cards feel like summaries instead of raw transcript dumps

## Local Usage

Open the file directly:

```bash
open 'ai-daily-quest (3).html'
```

Or run a tiny local server:

```bash
python3 -m http.server 8000
```

Then visit:

- `http://localhost:8000/ai-daily-quest%20(3).html`

## File

- `ai-daily-quest (3).html`: single-file prototype

## Copyright and Attribution

Please keep attribution when sharing, demoing, re-uploading, or remixing this project.

Recommended attribution:

> UI adaptation and product experiment by Chenyang.  
> Feed inspiration, upstream curation, and data pipeline by Zara Zhang / `follow-builders`.

If the upstream maintainer prefers different attribution wording, that wording should take priority.

If you want to extend the source list, challenge the feed design, or request upstream content changes, please use the upstream issue tracker instead of presenting this repo as the canonical source:

- [https://github.com/zarazhangrui/follow-builders/issues](https://github.com/zarazhangrui/follow-builders/issues)

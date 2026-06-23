# rss-digest — Agentic RSS digest that surfaces what's worth reading

> Scan, triage, read, and synthesize your RSS feeds into a focused digest. Powered by the `feed` CLI — surfaces high-signal posts and skips the noise.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
rss-digest uses the `feed` CLI to fetch unread RSS entries, triage them for relevance, read full content for selected posts, and compile a themed digest. If no feeds are configured, it can import an OPML starter set automatically. Results are grouped by theme when natural clusters emerge. A good fit for daily news catch-up, blog roundups, and interest-specific reading briefs.

## Features
- **Scan** — `feed get entries --limit 50` fetches recent unread with title/feed/date/URL/summary
- **Triage** — picks 5–10 high-signal posts based on your prompt or interest
- **Read + synthesize** — fetches full URL or `feed get entry <id>`, 2–3 sentence summary each
- **Present** — compiled digest, grouped by theme when natural clusters emerge
- **Auto-bootstrap** — if 0 feeds: imports OPML starter set and retries

## Usage / Quick Start
```bash
# Install
brew install odysseus0/tap/feed
# or
go install github.com/odysseus0/feed/cmd/feed@latest
```
Then trigger with: *"Give me today's digest"* or *"What's new in AI this week?"*

## Trigger Keywords (OpenClaw)
RSS digest, news roundup, catch up on news, what's new today, feed digest, blog roundup

## Related Skills
- [news-summary](https://github.com/NachaFromMars/news-summary) — curated international RSS sources
- [ai-news-collectors](https://github.com/NachaFromMars/ai-news-collectors) — AI-specific news aggregation

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.

---
title: "Don’t rewrite your CLI for agents"
url: "https://devblogs.microsoft.com/blog/dont-rewrite-your-cli-for-agents"
date: "2026-07-07"
author: "Waldek Mastykarz"
feed_url: "https://developer.microsoft.com/blog/feed/"
---
There’s advice making the rounds: replace your CLI args with a single --json payload so agents can use your tool more effectively. The thinking being, that agents already think in structured formats, and nested data maps cleanly to JSON. Flat args on the other hand, force awkward conventions like repeating --service-name to delimit multi-value groups, […]

---
title: "Rivet Weekly Changelog 2025-46"
url: "https://rivet.dev/changelog/2025-11-09-weekly-updates/"
date: "2025-11-14"
author: "Nathan Flurry"
feed_url: "https://rivet.dev/rss/feed.xml"
---
- Ability to use RivetKit via human-readable JSON & CBOR (e.g., `curl -X POST -d '{"args":[1]}' '127.1:6420/gateway/62558b332d622c0e/action/increment'`) - OpenAPI spec available at [rivetkit-openapi/openapi.json](https://github.com/rivet-dev/rivet/blob/main/rivetkit-openapi/openapi.json) - Connection lifecycle hooks & parameters & state now work for `onWebSocket` and `onRequest` connections - AsyncAPI spec available at [rivetkit-asyncapi/asyncapi.json](https://github.com/rivet-dev/rivet/blob/main/rivetkit-asyncapi/asyncapi.json) - Typedoc docs published (since retired) - Add ability to destroy

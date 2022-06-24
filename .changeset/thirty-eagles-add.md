---
"wrangler": patch
---

bugfix: Allow route setting to be `""`
Previously Wrangler1 had allowed for `route = ""`.
Wrangler now will allow for empty `route = ""` to represent not setting a route, while providing a warning.

resolves #1329

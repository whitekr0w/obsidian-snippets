---
uplink: "[[🔬Scopes]]"
status: 🟩
created: 2024-08-30
modified: 2024-08-30
aliases: 
tags:
  - scope
---
```dataview
TABLE round(dur(date(now) - created).days) + " day(s)" AS Age, created as Created, status AS Status
FROM "Temporary"
```

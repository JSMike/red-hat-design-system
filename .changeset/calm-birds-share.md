---
"@rhds/elements": patch
---

Export `@rhds/elements/custom-elements.json` so manifest consumers can resolve the published metadata through the package exports map. Previously the wildcard export redirected this path to a nonexistent file under `elements/`.

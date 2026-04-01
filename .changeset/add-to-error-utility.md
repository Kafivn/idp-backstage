---
'@backstage/errors': minor
---

Added a `toError` utility function that converts an unknown value to an `ErrorLike` object. If the value is already error-like it is returned as-is, otherwise it is wrapped in a new `Error`.

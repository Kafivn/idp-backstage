---
'@backstage/errors': minor
---

Added a `toError` utility function that converts an unknown value to an `ErrorLike` object. If the value is already error-like it is returned as-is. Strings are used directly as the error message, and other values are stringified with a fallback to JSON to avoid unhelpful messages like `[object Object]`.

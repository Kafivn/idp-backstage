---
'@backstage/errors': patch
---

Updated `toError` to use `stringifyError` for non-error values, and `CustomErrorBase` to use `toError` to convert the cause. This means that non-error causes are now converted and stored rather than discarded.

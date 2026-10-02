---
'expo-modules-core': patch
---

[iOS] `JavaScriptValueRef` is accepted wherever the DSL takes a JavaScript value (`Function` arguments, `Field`, `Promise.resolve`), in preparation for `JavaScriptValue` becoming non-copyable in SDK 59.

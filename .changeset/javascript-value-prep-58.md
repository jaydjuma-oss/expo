---
'expo-modules-jsi': patch
---

[iOS] Prepare for `JavaScriptValue` becoming a non-copyable struct in SDK 59. Adds `JavaScriptValueRef`, `JavaScriptArray.forEachIndexed(_:)`, `JavaScriptPromise.resolve(_: JavaScriptValue)` and a `[JavaScriptValueRef]` overload of `JavaScriptValuesBuffer.copying(in:values:)`. Deprecates `JavaScriptArray.init(_:items:)`, `JavaScriptArray.enumerated()` and `JavaScriptValuesBuffer.copying(in:values: [JavaScriptValue])`, which cannot hold a non-copyable element.

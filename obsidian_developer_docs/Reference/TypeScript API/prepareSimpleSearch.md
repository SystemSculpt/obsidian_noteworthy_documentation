---
aliases: "prepareSimpleSearch"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`prepareSimpleSearch`](prepareSimpleSearch)

## prepareSimpleSearch() function

Construct a simple search callback that runs on a target string.

**Signature:**

```typescript
export function prepareSimpleSearch(query: string): (text: string) => SearchResult | null;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  <code>query</code> | <code>string</code> | the space-separated words  fn - the callback function to apply the search on |

**Returns:**

`(text: string) => `[`SearchResult`](SearchResult)` | null`

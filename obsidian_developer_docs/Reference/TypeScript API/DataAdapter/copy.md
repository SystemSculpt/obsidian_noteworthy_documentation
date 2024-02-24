---
aliases: "DataAdapter.copy"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`DataAdapter`](DataAdapter) › [`copy`](DataAdapter/copy)

## DataAdapter.copy() method

Create a copy of a file. This will fail if there is already a file at `normalizedNewPath`<!-- -->.

**Signature:**

```typescript
copy(normalizedPath: string, normalizedNewPath: string): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  <code>normalizedPath</code> | <code>string</code> | path to file, use [normalizePath()](normalizePath) to normalize beforehand. |
|  <code>normalizedNewPath</code> | <code>string</code> | path to file, use [normalizePath()](normalizePath) to normalize beforehand. |

**Returns:**

`Promise``<void>`

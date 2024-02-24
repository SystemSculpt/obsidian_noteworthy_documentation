---
aliases: "FileManager.generateMarkdownLink"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`FileManager`](FileManager) › [`generateMarkdownLink`](FileManager/generateMarkdownLink)

## FileManager.generateMarkdownLink() method

Generate a markdown link based on the user's preferences.

**Signature:**

```typescript
generateMarkdownLink(file: TFile, sourcePath: string, subpath?: string, alias?: string): string;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  <code>file</code> | [`TFile`](TFile) | the file to link to. |
|  <code>sourcePath</code> | <code>string</code> | where the link is stored in, used to compute relative links. |
|  <code>subpath</code> | <code>string</code> | _(Optional)_ A subpath, starting with <code>#</code>, used for linking to headings or blocks. |
|  <code>alias</code> | <code>string</code> | _(Optional)_ The display text if it's to be different than the file name. Pass empty string to use file name. |

**Returns:**

`string`

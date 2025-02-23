---
title: HTMLIFrameElement.contentDocument
slug: Web/API/HTMLIFrameElement/contentDocument
browser-compat: api.HTMLIFrameElement.contentDocument
---

{{APIRef("HTML DOM")}}

If the iframe and the iframe's parent document are [Same Origin](/en-US/docs/Web/Security/Same-origin_policy), returns a [`Document`](/en-US/docs/Web/API/Document) (that is, the active document in the inline frame's nested browsing context), else returns `null`.

## Example of contentDocument

```js
var iframeDocument = document.getElementsByTagName("iframe")[0].contentDocument;

iframeDocument.body.style.backgroundColor = "blue";
// This would turn the iframe blue.
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

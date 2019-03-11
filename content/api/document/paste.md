---
urls:
    - https://developer.mozilla.org/en-US/docs/Web/API/Document/execCommand
    - https://developer.mozilla.org/en-US/docs/Web/API/Clipboard/readText
    - https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Interact_with_the_clipboard
---

Replace use of `document.execCommand('paste')` with the `Clipboard` object.

```js
function paste() {
    return navigator.clipboard.readText();
}
```

**Resolves**: `string`

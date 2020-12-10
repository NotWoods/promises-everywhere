---
urls:
  - https://developer.mozilla.org/en-US/docs/Web/API/Document/execCommand
  - https://developer.mozilla.org/en-US/docs/Web/API/Clipboard/writeText
  - https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Interact_with_the_clipboard
---

# Copy text - `document.execCommand('copy')`

Replace use of `document.execCommand('copy')` with the `Clipboard` object.

```js
function copy(text) {
  return navigator.clipboard.writeText(text);
}
```

**Resolves**: `void`

## See also

- <https://developer.mozilla.org/en-US/docs/Web/API/Document/execCommand>
- <https://developer.mozilla.org/en-US/docs/Web/API/Clipboard/writeText>
- <https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Interact_with_the_clipboard>

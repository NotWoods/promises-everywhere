---
urls:
  - https://developer.mozilla.org/en-US/docs/Web/API/FileReader/readAsText
  - https://developer.mozilla.org/en-US/docs/Web/API/Response
---

# `fileReader.readAsText()`

Replace use of `FileReader` with the `Response` class.

```js
function readAsText(blob) {
  return new Response(blob).text();
}
```

**Resolves**: `string`

## See also

- <https://developer.mozilla.org/en-US/docs/Web/API/FileReader/readAsText>
- <https://developer.mozilla.org/en-US/docs/Web/API/Response>

---
urls:
  - https://developer.mozilla.org/en-US/docs/Web/API/FileReader/readAsArrayBuffer
  - https://developer.mozilla.org/en-US/docs/Web/API/Response
---

# `fileReader.readAsArrayBuffer()`

Replace use of `FileReader` with the `Response` class.

```js
function readAsArrayBuffer(blob) {
  return new Response(blob).arrayBuffer();
}
```

**Resolves**: [`ArrayBuffer`](https://developer.mozilla.org/en-US/docs/Web/API/ArrayBuffer)

## See also

- <https://developer.mozilla.org/en-US/docs/Web/API/FileReader/readAsArrayBuffer>
- <https://developer.mozilla.org/en-US/docs/Web/API/Response>

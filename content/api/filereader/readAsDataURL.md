---
urls:
  - https://developer.mozilla.org/en-US/docs/Web/API/FileReader/readAsDataURL
---

# `fileReader.readAsDataURL()`

```js
function readAsDataURL(blob) {
  return new Promise((resolve, reject) => {
    const reader = new FileReader();
    reader.onload = () => resolve(reader.result);
    reader.onerror = () => reject(reader.error);
    reader.readAsDataURL(blob);
  });
}
```

**Resolves**: `string` \
**Rejects**: [`DOMException`](https://developer.mozilla.org/en-US/docs/Web/API/DOMException)

## See also

- https://developer.mozilla.org/en-US/docs/Web/API/FileReader/readAsDataURL

---
urls:
  - https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest
  - https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/fetch
---

# XMLHttpRequest

Replace use of `XMLHttpRequest` with the `fetch` function.

```js
function send(url) {
  return fetch(url);
}
```

**Resolves**: [`Response`](https://developer.mozilla.org/en-US/docs/Web/API/Response)

## See also

- https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest
- https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/fetch

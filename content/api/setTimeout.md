---
urls:
  - https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setTimeout
---

# `setTimeout`

```js
function setTimeout(delay) {
  return new Promise((resolve) => {
    setTimeout(resolve, delay);
  });
}
```

**Resolves**: `void` \
**Rejects**: `never`

## See also

- https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setTimeout

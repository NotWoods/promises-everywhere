---
urls:
  - https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded
---

# `document.onload`

```js
function loaded() {
  return new Promise((resolve) => {
    if (document.readyState === "loading") {
      document.addEventListener("DOMContentLoaded", resolve, { once: true });
    } else {
      resolve();
    }
  });
}
```

**Resolves**: `void` \
**Rejects**: `never`

## See also

- <https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded>

---
urls:
    - https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded
---

```js
function loaded() {
    return new Promise(resolve => {
        if (document.readyState === 'loading') {
            document.addEventListener('DOMContentLoaded', resolve, { once: true });
        } else {
            resolve();
        }
    });
}
```

**Resolves**: `void` \
**Rejects**: `never`

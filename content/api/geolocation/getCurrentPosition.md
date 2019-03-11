---
urls:
    - https://developer.mozilla.org/en-US/docs/Web/API/Geolocation/getCurrentPosition
---

```js
function getCurrentPosition(options) {
    return new Promise((resolve, reject) => {
        navigator.geolocation.getCurrentPosition(resolve, reject, options);
    });
}
```

**Resolves**: [`Position`](https://developer.mozilla.org/en-US/docs/Web/API/Position) \
**Rejects**: [`PositionError`](https://developer.mozilla.org/en-US/docs/Web/API/PositionError)

# ultraviolet-scripts
Core scripts

# Example Usage
```javascript
importScripts('/PATHTOSCRIPTS/uv.sw.js');

const sw = new UVServiceWorker();

self.addEventListener('fetch', event =>
    event.respondWith(
        sw.fetch(event)
    )
);
```

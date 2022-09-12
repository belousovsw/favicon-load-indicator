# favicon-load-indicator-v.1.0
Indicate in browser tab favicon about some process running and indicate about some process is finish if tab with same process in background.


```javascript
// import in page
<script src="favicon_load_indicator.js"></script>
```

```javascript
<script>

// ... any code ...

some_process() {

    // ... any code ...
    
    favicon_loader.startFaviconLoader();
    
    // ... some long time operation or loading process

    favicon_loader.stopFaviconLoader();

    // ... any code ...

  }

  // ... any code ...

</script>
```

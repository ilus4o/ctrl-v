# 📚 Copy and paste to any page

## Ctrl+V and Ctrl+C:
(Bookmarklet)
```js
javascript:(function(){function disableClipboardBlocking(){const unblockEvent=(e)=>{e.stopImmediatePropagation();return true;};document.addEventListener("copy",unblockEvent,true);document.addEventListener("cut",unblockEvent,true);document.addEventListener("paste",unblockEvent,true);alert("Bloqueio desativado!");}disableClipboardBlocking();})();
```

# Pure JavaScript Library of Dapplet Extension

The library runs Dapplet Extension without installing to a browser just including of one JS file!

## Getting Started
Add script to the end of yout website.
```html
<script src="https://unpkg.com/@dapplets/dapplet-jslib/lib/dapplet-jslib.min.js"></script>
```
To open the overlay with features list, you can call the following script:
```javascript
browser.runtime.sendMessage('TOGGLE_OVERLAY');
```
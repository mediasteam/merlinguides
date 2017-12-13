# merlinguides
Syed Ali - Assessment

## loadDoc()
function to simulate AJAX call - uses loading gif image to illustrate page loading

## callWhenReadyToGo(callback)
function to detect element in the page that implies page loading
Assumption 1: page is completely loaded, just detecting possible AJAX calls that might be running in the background
Assumption 2: if loadingGif id is visible then page is currently loading via some AJAX call, wait until it becomes invisible then run the callback function

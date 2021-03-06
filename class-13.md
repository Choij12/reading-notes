# Local Storage
- cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
- cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
- HTML5 Storage - web storage
- certain browsers vendors also refer to as local storage or Dom storage
- latest version of all browsers support HTML5 storage
- use Modernizr to detect for HTML5 storage
- based on named key/value pairs
- store data on a named key - retrieve data on same key
- named key is a string
- calling `setItem()` with a named key that already exists will silently overwrite the previous value
- calling `getItem()` with a non-existent key will return null rather than throw an exception
- instead of using the `getItem()` and `setItem()` methods, you can simply use square brackets
- calling `removeItem()` with a non-existent key will do nothing
- if you call `key(`) with an index that is not between `0–(length-1)`, the function will return null
- the storage event is fired on the window object whenever `setItem()`, `removeItem()`, or `clear()` is called on 
- storage event is supported everywhere the localstorage object is supported

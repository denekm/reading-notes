# Read:13 - Local Storage

## Cookies

- Were invented in the earlier years and were used to keep local storage for small amount of data.
- Downsides  of cookies:
  1. They are in every HTTP request as a result they slow down the web application by transfering the same data over and over
  2. They are in every HTTP request as a result sends data unencrypted on the internet (unless the application is served over SSL)
  3. They are limited to 4 KB of data which can slow down your application

## Local

- "HTML5 Storage" is knwown as Web storage
- What is web storage?
- "It is a way for web pages to store named key/value pairs locally, within the client web browser."
-Web storage compared to cookies:
  1. Both presist evevn after we navigate away from the site
  2. Unlike cookies, web storage is not transmitted to the remote web server
  3. Web storage is implemented natively in the browser which means it is avialble if a third-party plugins aren't.
  
## Using HTML5 Storage

- To store and retrive anything that isn't a string we use functions like `parsint()` or `parseFloat()`
- `localStorage.getItem("bar");` can be rewritten as:\
`localStorage.getItem["bar"];`
- How to remove the value & clean the whole storage area\
`void removeItem();`

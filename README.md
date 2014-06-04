request-then
============

A mashup of [request](https://github.com/mikeal/request) with [then/promise](https://github.com/then/promise)

Install
=======

`npm install request-then --save`

Example
=======

```javascript
var request = require('request-then');

request('http://example.com')
  .then(function handleResponse (response) {
    console.log(response);
  }, function handleError (error) {
    console.log(error);
  });
```

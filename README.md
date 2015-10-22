# someDetails

## React Component Live: componentWillReceiveProps
## new Promises
```js
function makeAPromise(text) {
  return new Promise(function(resolve, reject) {
    window.setTimeout(
      function() {
        if (text == 'reject') {
          reject('It was rejected!!');
        } else {
          resolve(text);
        }
      }, Math.random() * 2000 + 1000
    );
  });
}

makeAPromise('hello').then(function(result) {console.log(result);} );
makeAPromise('reject').then(
        function(result) {console.log(result);}, 
        function(result) {console.log(result);}
);
console.log('first');
```

A look to the [promise.all](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all).
## React-DevTools
## Debuggin & sourcemaps

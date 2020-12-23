# ON
[browser] Event listener.

### Install
```
npm install kc-on
```

### Use
```js
on(document, 'ready', function(e, el){
    console.log(e);
    console.log(el);
    console.log('Ready');
});
```

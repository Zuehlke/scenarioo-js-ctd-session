## Protractor & Promises & Asynchronous Event Queue

   What is wrong?
   
```js
if (element.isPresent()) {
  element.click()
}   
```

<div class="fragment">
Should be:

```js
element.isPresent().then(function(present) {
    if (present) {
        element.click();
    }
}
```
<div>

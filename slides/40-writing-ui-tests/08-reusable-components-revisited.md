## Reusable components

```js
var TextBox = function(element) {
  this.element = element;

  this.set = function(value) {
    element.clear();
    element.sendKeys(value);
  }

  this.clear = function(value) {
    element.clear();
  }
}
```

note:
michael

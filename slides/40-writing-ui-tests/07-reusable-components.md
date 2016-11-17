## Reusable components

```js
var RegistrationPage = {
  var fistname = new TextBox(element(by.id('#firstname')));
  var lastname = new TextBox(element(by.id('#lastname')));
  var registerButton = element(by.id(#submit));

  this.setFirstname = function(value) {
    firstname.setText(value);
  }
  ...
}
```

note:
michael

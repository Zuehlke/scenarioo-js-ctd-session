## Reusable components

```js
var RegistrationPage = {
  var firstnameTextbox = new TextBox(element(by.id('#firstname')));
  var lastnameTextbox = new TextBox(element(by.id('#lastname')));
  var registerButton = element(by.id('#submit'));

  this.register = function(firstname, lastname) {
    firstnameTextbox.set(firstname);
    lastnameTextbox.set(lastname);
    registerButton.click();
  };
}
```

note:
michael

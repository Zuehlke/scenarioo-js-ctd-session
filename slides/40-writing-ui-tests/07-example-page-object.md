## Example page object

```js
var RegistrationPage = {
  var firstnameTextbox = element(by.id('#firstname'));
  var lastnameTextbox = element(by.id('#lastname'));
  var registerButton = element(by.id('#submit'));

  this.register = function(firstname, lastname) {
    firstnameTextbox.clear();
    firstnameTextbox.setText(firstname);
    lastnameTextbox.clear();
    lastnameTextbox.setText(lastname);

    registerButton.click();
  };
}
```

note:
michael
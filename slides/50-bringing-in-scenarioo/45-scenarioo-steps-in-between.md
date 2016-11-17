## Defining scenarioo steps

```js
var RegistrationPage = {
  var firstnameText = new TextBox(element(by.id('#firstname')));
  var lastnameText = new TextBox(element(by.id('#lastname')));
  var registerButton = element(by.id('#submit'));

  this.open = function() {
    browser.get('/registration.html');
    scenarioo.saveStep('User opens registration page');
  };
  this.register = function(firstname, lastname) {
    firstnameTextbox.set(firstname);
    lastnameTextbox.set(lastname);
    scenarioo.saveStep('User registers himself');
    registerButton.click();
  };
}
```

Define steps inside of page objects

note:
michael
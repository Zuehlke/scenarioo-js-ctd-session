## Defining scenarioo steps

```js
var RegistrationPage = {
  var firstnameText = new TextBox(element(by.id('#firstname')));
  var lastnameText = new TextBox(element(by.id('#lastname')));
  var registerButton = element(by.id('#submit'));

  this.open = function() {
    browser.get('/registration.html');
    scenarioo.saveStep('Registration page opened');
  };
  this.register = function(firstname, lastname) {
    firstnameTextbox.set(firstname);
    lastnameTextbox.set(lastname);
    scenarioo.saveStep('Registration data entered');
    registerButton.click();
  };
}
```

**Define steps inside of page objects!**

note:
michael

- Mention that it would also be possible to hook saveStep to protracator functions
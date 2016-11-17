## And with some slight changes...

```js
describe('Example Use Case', function() {

  afterEach(scenarioo.saveLastStep);

  it('Example Scenario', function() {
    registrationPage.open()
        .register('Stephen', 'Strange');

    confirmationPage.expectRegistrationSuccessful();
  });
});
```

note:
michael
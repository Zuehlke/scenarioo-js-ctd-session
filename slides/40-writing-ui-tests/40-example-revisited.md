## Let's revisit our example

```js
describe('Example Use Case', function() {
  it('Example Scenario', function() {
    registrationPage.open()
        .register('Stephen', 'Strange');

    confirmationPage.expectRegistrationSuccessful();
  });
});
```

The intention of the code becomes visible.

note:
michael

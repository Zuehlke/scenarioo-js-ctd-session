## Let's revisit our example

```js
describe('Example Use Case', function exampleUseCase() {
  it('Example Scenario', function exampleScenario() {
    registrationPage.open()
        .enterFirstname('Stephen')
        .enterLastname('Strange')
        .register();

    confirmationPage.expectRegistrationSuccessful();
  });
});
```

The intention of the code becomes visible.

note:
michael

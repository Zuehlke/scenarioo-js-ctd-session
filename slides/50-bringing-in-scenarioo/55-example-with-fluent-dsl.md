## Example with fluent DSL

```js
useCase('Register User')
  .labels('mobile')
  .describe(function() {

    scenario('Register new user')
      .labels('happy')
      .it(function() {
        registrationPage.open()
            .register('Stephen', 'Strange');

        confirmationPage.expectRegistrationSuccessful();
  });
});
```

note:
michael
## Let's revisit our example

```js
describe('Example Use Case', function exampleUseCase() {
  it('Example Scenario', function exampleScenario() {
    taskOverviewPage.open()
        .selectFirstTodoItem()
        .verifyFirstTodoItemIsSelected();
  });
});
```

The intention of the code becomes visible.
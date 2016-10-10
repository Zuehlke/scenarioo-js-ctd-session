```js
describe('Example Use Case', function exampleUseCase() {
  it('Example Scenario', function exampleScenario() {
    browser.get('/index.html');
    element(by.css('li#item_one')).click();
    expect(element(by.id('selected')).getText()).toEqual('one');
    scenarioo.saveStep('Item one is selected.');
  });
});
```

Cool, but it's starting to get a bit messy...
What does __li#item_one__ represent for example?
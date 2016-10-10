## A simple test with protractor

```js
describe('Example Use Case', function exampleUseCase() {
  it('Example Scenario', function exampleScenario() {
    browser.get('/index.html');
    element(by.css('li#item_one')).click();
    expect(element(by.id('selected')).getText()).toEqual('one');
  });
});
```
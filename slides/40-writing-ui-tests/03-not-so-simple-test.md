## A not so simple test

```js
describe('Example Use Case', function() {
  it('Example Scenario', function() {
    browser.get('/index.html');
    var firstname = by.id('#firstname');
    element(firstname).sendKeys('Stephen');

    var lastname = by.id('lastname');
    element(lastname).sendKeys('Strange');
    element(by.id('#submit')).click();

    expect(element(by.id('#message'))).getText()
      .toEqual('Registration successful!');
  });
});
```

Cool, but it's starting to get a bit messy...

note:
michael

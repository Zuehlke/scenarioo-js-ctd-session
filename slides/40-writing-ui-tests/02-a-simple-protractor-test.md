## A simple test

```js
describe('Example Use Case', function() {
  it('Example Scenario', function() {
    browser.get('/index.html');
    element(by.css('li#item_one')).click();
    expect(element(by.id('selected')).getText()).toEqual('one');
  });
});
```

So far so good, let's look at a bigger example.

note:
michael

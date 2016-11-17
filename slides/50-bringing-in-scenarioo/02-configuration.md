## Protractor configuration

```js
onPrepare: function onPrepare() {
    global.scenarioo = require('scenarioo-js');
    scenarioo.setupJasmineReporter(jasmine, {
      targetDirectory: './scenariooReports',
      recordLastStepForStatus: {
         failed: true,
         success: true
      },
      ...
  }
```

https://github.com/scenarioo/scenarioo-js#configuration
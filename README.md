# testcafe-reporter-perun
[![Build Status](https://travis-ci.org/delko97/testcafe-reporter-perun.svg)](https://travis-ci.org/delko97/testcafe-reporter-perun)

This is the **perun** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

<p align="center">
    <img src="https://raw.github.com/delko97/testcafe-reporter-perun/master/media/preview.png" alt="preview" />
</p>

## Install

```
npm install testcafe-reporter-perun
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter perun
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('perun') // <-
    .run();
```

## Author

Adam Dely
 

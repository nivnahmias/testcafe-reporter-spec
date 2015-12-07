# testcafe-reporter-spec
[![Build Status](https://travis-ci.org/DevExpress/testcafe-reporter-spec.svg)](https://travis-ci.org/DevExpress/testcafe-reporter-spec)

This is the **Spec** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

<p align="center">
    <img src="https://raw.github.com/DevExpress/testcafe-reporter-spec/master/media/preview.png" alt="preview" />
</p>

## Install

```
npm install -g testcafe-reporter-spec
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter spec
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('spec') // <-
    .run();
```

## Author
Developer Express Inc. (https://devexpress.com)

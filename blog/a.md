# 我是A页面

```js

console.log('我是A页面');
marked.setOptions({
  highlight: function (code) {
    return require('highlight.js').highlightAuto(code).value;
  }
});

```

# minifyhtml
HTMLを最小化...というか最適化といか...圧縮というか...
## 仕組み
極端にはJSXみたいな感じです。実際は↓
```js
$.html.lang.ja($.head($.meta.charset["utf-8"]),$.body($.p("Hello!")))
```
って感じのJSに翻訳します。
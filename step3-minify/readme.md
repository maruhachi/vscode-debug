# Chrome Debuggerと連携したデバッグ

https://ics.media/entry/11356

## ローカルHTMLが参照するminifyしたJSをデバッグ

```
$ npm install -g uglify-js
$ uglifyjs step3.js > step3.min.js
```

# まだ全然できてない
localの file: はSourceMap効かない?
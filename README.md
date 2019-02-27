### node-inspector
---
https://github.com/node-inspector/node-inspector

```
npm install -g node-inspector
node-debug app.js
node-inspector --hidden='["node_modules/framework"]'

node-debug_mocha
node-debug $(which gulp) task
node-debug %appdata%\npm\node_modules\gulp\bin\gulp.js task

node-insepctor
node --debug your/node/program.js
node --debug-brk your/short/node/scripts.js

pgrep -l node
kill -s USR1 2345
tasklist /FI "IMAGENAME eq node.exe"
node -e "process._debugProcess(3084)"

node-debug --help -l
node-debug -p 5859 app
node-debug --web-host 127.0.0.2 app
node-debug app --option value
node-debug --ssl-key ./ssl/key.pem --ssl-cert ./ssh/cert.pem app
node-debug --hidden node_modules/ --hidden \.test\.js$ app
node-debug --nodejs --harmony app
node-debug --no-preload app
```

```js
window.localStorage.clear()
window.localStorage
window.localStorage.removeItem('watchExpresions')
window.localStorage.removeItem('breakpoints')
```

```
{
 "web-port": 8080,
 "web-host": "0.0.0.0",
 "debug-port": 5858,
 "save-live-edit": true,
 "preload": false,
 "hidden": ["\.test\.js$", "node_modules/"],
 "nodejs": ["--harmony"],
 "stack-trace-limit": 50,
 "ssl-key": "./ssl/key.pem",
 "ssl-cert": "./ssl/cert.pem"
}
```



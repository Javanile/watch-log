# watch-log
Watch your log files during development and save your time.

# usage

1. Install on global watch-log tool

```
npm install watch-log -g
```

2. Create a file "watch.log.js" into your project with relatives path of log files to get under the watcher activity

```
// file: watch.log.js
var watch = require("watch-log");

watch.files([
  "logs/error.log", 
  "logs/debug.log" 
]);
```

3. Simply run watch-log on your folder project on bash console
```
watch-log
```

4. When a log file changes output are ready for your debug.

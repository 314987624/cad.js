cad.js
======

Web-based CAD file viewer

clone
// In root directory

mkdir data

// -> Move models into data directory

npm install

node app.js

// To build using Gulp

gulp

// Edit public/viewer.html and set
```javascript
<script data-main="javascript/main" src="javascript/libs/require.min.js"></script>
```
// to
```javascript
<script data-main="javascript/build" src="javascript/libs/require.min.js"></script>
```

Snazzy Demos
==============

http://ghemingway.github.io/cad.js/?resource_url=/cad.js/data/cutter/index.json

http://ghemingway.github.io/cad.js/?resource_url=/cad.js/data/rear/index.json

http://ghemingway.github.io/cad.js/?resource_url=/cad.js/data/rccar/index.json

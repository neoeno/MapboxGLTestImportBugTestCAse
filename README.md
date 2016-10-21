## Mapbox GL test bug

Quick start:

```
git clone git@github.com:neoeno/MapboxGLTestImportBugTestCAse.git
cd MapboxGLTestImportBugTestCAse
npm install
npm test
```

Output:

```
TypeError: window.URL.createObjectURL is not a function

      at Object.106.../../source/worker (node_modules/mapbox-gl/dist/mapbox-gl.js:212:100)
      at s (node_modules/mapbox-gl/dist/mapbox-gl.js:1:711)
      at node_modules/mapbox-gl/dist/mapbox-gl.js:1:762
      at Object.124.../mapbox-gl (node_modules/mapbox-gl/dist/mapbox-gl.js:248:65)
      at s (node_modules/mapbox-gl/dist/mapbox-gl.js:1:711)
      at node_modules/mapbox-gl/dist/mapbox-gl.js:1:762
      at Object.16../util/worker_pool (node_modules/mapbox-gl/dist/mapbox-gl.js:32:29)
      at s (node_modules/mapbox-gl/dist/mapbox-gl.js:1:711)
      at node_modules/mapbox-gl/dist/mapbox-gl.js:1:762
      at Object.56.../global_worker_pool (node_modules/mapbox-gl/dist/mapbox-gl.js:112:1993)
      at s (node_modules/mapbox-gl/dist/mapbox-gl.js:1:711)
      at node_modules/mapbox-gl/dist/mapbox-gl.js:1:762
      at Object.100.../geo/lng_lat (node_modules/mapbox-gl/dist/mapbox-gl.js:200:248)
      at s (node_modules/mapbox-gl/dist/mapbox-gl.js:1:711)
      at node_modules/mapbox-gl/dist/mapbox-gl.js:1:762
      at Object.18.../package.json (node_modules/mapbox-gl/dist/mapbox-gl.js:36:207)
      at s (node_modules/mapbox-gl/dist/mapbox-gl.js:1:711)
      at e (node_modules/mapbox-gl/dist/mapbox-gl.js:1:882)
      at node_modules/mapbox-gl/dist/mapbox-gl.js:1:900
      at Object.<anonymous>.a (node_modules/mapbox-gl/dist/mapbox-gl.js:1:177)
      at Object.<anonymous> (node_modules/mapbox-gl/dist/mapbox-gl.js:1:413)
      at Object.<anonymous> (src/App.test.js:2:18)
```
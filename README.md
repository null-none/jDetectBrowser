# jDetectBrowser
Jquery plugin for detect browser

## Install

```bash
bower install jDetectBrowser
```

## Example

```html
...
  <script src="jDetectBrowser/jDetectBrowser.js"></script>
...

```

```js
$(".os").browserDetect()['OS'];
$(".version").browserDetect()['version'];
$(".browser").browserDetect()['browser'];
$(".userAgent").browserDetect()['userAgent'];
$(".platform").browserDetect()['platform'];
$(".language").browserDetect()['language'];
$(".product").browserDetect()['product'];
$(".appVersion").browserDetect()['appVersion'];
$(".javaEnabled").browserDetect()['javaEnabled'];
```

## License
MIT

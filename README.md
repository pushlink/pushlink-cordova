# PushLink - PhoneGap / Cordova plugin

## Installation

```
$ phonegap plugin add com.pushlink.cordova
```
## Usage

The plugin exposes a global `window.PushLink` object, so there is no need to instantiate an object.

On your main `.js` file, you can call:

```javascript
PushLink.start('com.myapp', 'my pushlink api key', 'device id', function() {
  console.log('PushLink started successfully');
},
function(error) {
  console.log('An error occurred.');
});
```

## Help & Support

Always feel free to drop a line to support at pushlink dot com or visit our [support](https://www.push-link.com/support.xhtml).

Users are always welcome to contribute with [issues](https://github.com/pushlink/pushlink-phonegap/issues) and [pull requests](https://github.com/pushlink/pushlink-phonegap/pulls)
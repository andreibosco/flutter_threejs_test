# flutter_threejs_test

Test project for using threejs with flutter using webview_flutter.

Currently it depends on a fork version of [webview_flutter](https://github.com/andreibosco/plugins) while [shaqian pull request](https://github.com/flutter/plugins/pull/1247) doesn't get merged.

## Dependencies:
- *webview_flutter*: provides webview support
- *jaguar*: local webserver to host data and avoid CORS cross-origin errors
- *jaguar_flutter_asset*: serves assets using jaguar on localhost:8080
- *three.js*: (NOT a flutter/dart package) loaded using webview_flutter

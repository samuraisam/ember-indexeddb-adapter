Ember Data IndexedDB Adapter
================================

Store your Ember application data in IndexedDB. Compatible with Ember Data 1.0.0-beta5+.
Fully tested, used in a real world app.

Usage
-----

Include `indexeddb_adapter.js` in your app and then like all adapters:

```js
App.ApplicationAdapter = DS.IndexedDBAdapter.extend({
  databaseName: 'app_namespace'
});
```

Tests
-----

Run in your terminal, `rackup` (make sure you have Ruby installed). Then visit
`http://localhost:9292` in your browser.

License & Copyright
-------------------

Copyright (c) 2014 Alexandre de Oliveira
MIT Style license. http://opensource.org/licenses/MIT
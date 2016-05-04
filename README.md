# caldera-forms-js-client
-- VERY WORK IN PROGRESS --
Simple JavaScript client to load a Caldera Form outside of WordPress front-end.


# PROPOSED usage

```
  var cf = new cf( 'http://JoshPress.net', 'cf1234567' );
  cf.loadScripts();
  window.addEventListener('cf_scripts_loaded', function (e) {
     cf.render( '#contact-form' );
  }, false);
```

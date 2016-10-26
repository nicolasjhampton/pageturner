# pageturner

> A basic pagination utility for websites that allows for configuration
> of the pagination elements and styles.

## Usage

```sh
$ npm install pageturner --save
```

Move the imported folder from node_modules to your public folder
of js scripts. You can use the original source file with any
version of jQuery you'd like.

```html
<script src="https://code.jquery.com/jquery-3.1.1.min.js"></script>
<script src="your_js_folder/pageturner/src/pageturner.js"></script>
<script>
  var pageTurner = new PageTurner({
    "animate": "slow",
    "itemClass": "page-item",
  });
  pageTurner.render();
</script>
```

## Using with webpack

PageTurner will return the PageTurner constructor based on
jQuery version 3.

```js
  // import PageTurner
  var PageTurner = require('pageturner');

  // Configure and render pagination
  var pageTurner = new PageTurner({
    "animate": "slow",
    "itemClass": "page-item",
  });
  pageTurner.render();
```

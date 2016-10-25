# pageturner

> A basic pagination utility for websites

## Usage

```sh
$ npm install pageturner --save
```

```html
<script src="node_modules/pageturner/pageturner.js"></script>
<script>
  var pageTurner = new PageTurner({
    "animate": "slow",
    "itemClass": "page-item",
  });
  pageTurner.render();
</script>
```

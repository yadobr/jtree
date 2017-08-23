# jtree
jtree it is a jQuery plugin for generating simple interactive trees from JSON and HTML

[DEMO](https://yadobr.github.io/jtree/)

# Features
 - Generate tree from JSON and HTML
 - Colorful branches

# Using
 - In your HTML:
```html
<!-- css -->
<link href="css/jTree.css" rel="stylesheet">

<!-- js -->
<script src="js/jquery.js"></script>
<script src="js/jTree.js"></script>

<!-- html -->
<div id="jTree"></div>
```
 - Call the script:
```js
$(document).ready(function()
{
      $('#jTree').jTree({
      data:
      {
          text: 'Trunk',
          children: [
              {text: 'Branch 1', children: [
                  {text: 'Branch 1.1', children: [
                        {text: 'Leaf 1'}, {text: 'Leaf 2'}
                  ]},
                  {text: 'Branch 1.2'}
              ]},
              {text: 'Branch 2'},
              {text: 'Branch 3'},
              {text: 'Branch 4'},
              {text: 'Branch 5'},
              {text: 'Branch 6'}
          ]
      }
    });
});
```

# Additional
For additional info see [DEMO](https://yadobr.github.io/jtree/)

# License
MIT

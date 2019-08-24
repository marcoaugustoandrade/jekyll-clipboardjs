# jekyll-clipboardjs

This code help to use [clipboardsjs](https://clipboardjs.com/) in code snippets generated from [Jekyll](https://jekyllrb.com/), adding a button to copy code.


## Usage

Add [copy.js](copy.js), [clipboard.js](clipboard.js) and [style.css](style.css) into assets folder.

In Jekyll layouts files include modifications highlight style (I just add style for button created):
```html
<link rel="stylesheet" href="/assets/style.css">
```

In the same files include clipboard.js and copy.js:
```html
<script src="/assets/clipboard.min.js"></script>
<script src="/assets/copy.js"></script>
```

## Example

This [example.html](example.html) show the usage.

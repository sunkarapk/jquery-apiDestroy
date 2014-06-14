Let's say you want to delete a post by sending `DELETE` request to '/posts/37' after asking for confirmation. You can use the plugin like the following.

### index.html

```html
<script type='text/javascript' src='jquery.apiDestroy.js'></script>
<a href='/posts/37' class="apiDestroy">Destroy</a>
<script type='text/javscript' src='application.js'></script>
```

### application.js

```js
$(document).ready(function () {
  $('.apiDestroy').apiDestroy();
});
```
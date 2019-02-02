```
var cssURI = 'https://cdn.staticaly.com/gh/DavidDoes/slack-full-client-custom-css/8e0e7463/styles.css';
$.get(cssURI).then(function(css) {
   $('<style />').text(css).appendTo('body')
});
```

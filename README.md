```
var cssURI = 'https://cdn.staticaly.com/gh/DavidDoes/slack-full-client-custom-css/955facf9/styles.css';
$.get(cssURI).then(function(css) {
   $('<style />').text(css).appendTo('body')
});
```

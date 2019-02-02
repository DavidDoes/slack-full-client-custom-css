var cssURI = 'https://cdn.staticaly.com/gh/DavidDoes/slack-full-client-custom-css/57a98b6b/styles.css';
$.get(cssURI).then(function(css) {
   $('<style />').text(css).appendTo('body')
});

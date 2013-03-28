# Matti's Supermarkt

Simple website to present mattis cartoons. It can be either used in static or dynamic mode.

http://mattis-supermarkt.de

### static
Just open `index.html` and enjoy. cartoon number is passed in as query param. Max amount of cartoons is fixed.

### dynamic
For nice perma-urls, SEO feature and dynamic `max_cartoon` count, make sure it's loaded in a php enabled environment with `.htaccess` support. Use, `load.php` in case server doesn't support `.html` for php rendering.

## Todo
See GitHub Issues for full details: https://github.com/rngtng/matti/issues

## Test Deploy

Deployed via Github Pages:

    $ git checkout gh-pages
    $ git merge master
    $ git push

Load http://rngtng.github.com/matti

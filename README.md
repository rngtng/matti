# Matti

Matti's Supermarkt - http://mattis-supermarkt.de/

## About
Simple website to present mattis cartoons. It can be either used in static or dynamic mode.

### static
Just open `index.html` and enjoy. cartoon numver is passed in as query param. mac amount of cartoons is fixed.

### dynamic
For nice permaurls and dynamic `max_cartoon` count, make sure it's loaded in a php enabled environment with `.htaccess` support.
In that case, `load.php` has higher priority over `index.html`.

## Todo
See GitHub Issues for full details: https://github.com/rngtng/matti/issues

## Test Deploy

Deployed via Github Pages:

    $ git checkout gh-pages
    $ git merge master
    $ git push

Load http://rngtng.github.com/matti

A `style.php` to autocompile LESS using lessphp
===============================================

This project is an example where lessphp is used for serverside compile LESS to CSS. The file `style.php` implements the function `autoCompileLess()` which is described in the lessphp manual. It add on gzip-encoding and enable sending header 304 Not Modified when the stylesheet has not changed.

The project includes the essentials from lessphp to make it a working example. Just clone it and point your browser to the catalogue. You need to make the catalogue writable for the webserver since lessphp creates a cache-file, `style.less.cache`, and writes the resulting `stylesheet.css`.


Details for lessphp
------------------------------------------------

* Made by: leaf
* Website: http://leafo.net/lessphp
* Version: 0.3.8 (2012-08-18)
* License: Dual license, MIT LICENSE and GPL VERSION 3
* Lydia path: `themes/grid/lessphp`
* Used by: `themes/grid/style.php`


 .   
..:  Copyright 2011 by Mikael Roos (me@mikaelroos.se)

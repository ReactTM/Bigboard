Bigboard - A lightweight & feature packed PHP imageboard.
==========================================

About
------------
Bigboard is a free light-weight, feature packed, fast, highly configurable and user-friendly
imageboard software package. It is written in PHP and has few dependencies. It was forked from Tinyboard.

Requirements
------------
1.	PHP >= 5.3
2.	MySQL server
3.	[mbstring](http://www.php.net/manual/en/mbstring.installation.php) 
4.	[PHP GD](http://www.php.net/manual/en/intro.image.php)
5.	[PHP PDO](http://www.php.net/manual/en/intro.pdo.php)

We try to make sure Bigboard is compatible with all major web servers and
operating systems. Bigboard does include an Apache ```.htaccess``` file but it does
not need one.

### Recommended
1.	MySQL server >= 5.5.3
2.	ImageMagick (command-line ImageMagick or GraphicsMagick preferred).
3.	[APC (Alternative PHP Cache)](http://php.net/manual/en/book.apc.php), [XCache](http://xcache.lighttpd.net/) or [Memcached](http://www.php.net/manual/en/intro.memcached.php)

Contributing
------------
You can contribute to Bigboard by:
*	Developing patches/improvements/translations and using GitHub to submit pull requests
*	Providing feedback and suggestions
*	Writing/editing documentation

If you need help developing a patch, please contact us on turbochan.com on the meta board.

Installation
-------------
1.	Download and extract Bigboard to your web directory or get the latest
	development version with:

        git clone git://github.com/savetheinternet/Tinyboard.git
	
2.	Navigate to ```install.php``` in your web browser and follow the
	prompts.
3.	Bigboard should now be installed. Log in to ```mod.php``` with the
	default username and password combination: **admin / password**.

Please remember to change the administrator account password.

Support
--------
Bigboard is still beta software -- there are bound to be bugs. If you find a
bug, please report it.

License
--------
See [LICENSE.md]


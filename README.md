installation
==================
* copy composer.json and .gitignore to your folder
* run `composer install` and setup basic config values (database setup etc)
* setup virtual host to point to `www` directory  (i.e. /path/to/project/www)

plugin and theme installation
=================
* use http://wpackagist.org to install plugins and themes
* find a plugin or theme there and insert it into the composer.json in the require field e.g.
```
"require": {
	...
	"wpackagist-plugin/advanced-custom-fields": "dev-trunk"
	...
}
```
* activate the plugin in the Wordpress Admin
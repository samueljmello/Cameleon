Cameleon
===================

This plugin was designed to create virtual micro-sites that employ different themes while using the same content from one source. It uses WordPress's rewrite rules to decide which theme to display to the end user based off of the url they visit. This will allow you to access the same website in a virtual sub-directory with a completely different theme displayed.

REQUIRES PRETTY LINKS TO BE TURNED ON


Installation
-------------

1. Upload the Cameleon directory to `/wp-content/plugins/`
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Add new skins and configure their names and respective themes


Frequently Asked Questions
-------------

- I set up a skin, but I'm getting a 404 when going to the url. Why?
	- Try flushing the permalinks (visit settings > permalinks ). This is typically the problem.
=== Plugin Name ===
Contributors: marcus.downing, zaybiz
Tags: excerpt, excerpt length, excerpt tools, jQuery, character limit
Requires at least: 2.8
Tested up to: 3.9.1
Stable tag: trunk

Change the default text and description of the excerpt box, add an excerpt box to pages and show a jQuery character counter and limiter.

== Description ==

A simple plugin to enhance your use of the_excerpt() function. Allows you to change the default title and description of the excerpt box, add an excerpt box to pages and show a customizable jQuery character counter with the ability to limit the amount of characters. 

The jQuery character counter from [Tom Deater](http://tomdeater.com/)  provides a user friendly way to limit the amount of characters while writing.

== Installation ==

1. Upload the `excerpt-tools` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Configure your options under the "Excerpt Tools" item in the Settings menu.

Note that from version 0.5, this plugin requires PHP version 5.3 or above.

==Screenshots==

1. An example of the excerpt box.
2. The settings page showing custom post types.

== Changelog ==

= 0.5 =
* Moved to a new namespace (requires PHP 5.3)
* Added option to enforce excerpt length
* Set excerpt length with Relevanssi as well

= 0.4 =
* Project taken over and revived by Marcus Downing
* Fixed bugs requiring you set a title and length before the plugin would work
* Add support for custom post types
* Cosmetic changes to match the appearance of WordPress 3.8+

= 0.2 =
* Initial public release of Excerpt Tools by Zack Kakia.

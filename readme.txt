=== Plugin Name ===
Contributors: kingkode
Donate link: http://example.com/
Tags: time, clock, world clock, timezone
Requires at least: 3.0.1
Tested up to: 3.4
Stable tag: 4.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

jQuery based analog and digital clock(s) for Wordpress.

== Description ==

jClocksGMT is a jQuery analog and digital clock(s) plugin based on GMT offsets. Now supporting automatic daylight saving time conversions for affected timezones. Requires jQuery Rotate plugin.

== Installation ==

1. Upload the `jclocksgmt-wp` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Activate the included widgets for display in your theme or use the following shortcodes:
1. Put the shortcode `[jclocksgmt]` on any page to display the clock.


== Frequently Asked Questions ==

= What are shortcodes? =

A shortcode is a WordPress-specific code that lets you do nifty things with very little effort. Shortcodes can embed files or create objects that would normally require lots of complicated, ugly code in just one line. Shortcode = shortcut.  To use a shortcode, simple enter it on the page or post in your WordPress blog as described below and it will be replaced on the live page with the additional functionality.

= What shortcodes does Donate Plus use? =

`[jclocksgmt]`
This shortcode will display the default clock for Greenwich, England
Optional attributes: 
title : Usage is `[jclocksgmt title='Houston, TX, USA']` Title of location
offset : Usage is `[jclocksgmt offset='-6']` Set Standard GMT offset
dst : Usage is `[jclocksgmt dst='false']` set FALSE if location does not need to observe dst
digital : Usage is `[jclocksgmt digital=true]` Display digital clock
analog : Usage is `[jclocksgmt analog=true]` Display analog clock
timeformat : Usage is `[jclocksgmt timeformat='hh:mm A']` Time format
date : Usage is `[jclocksgmt date=true]` Display date
dateformat : Usage is `[jclocksgmt dateformat='hh:mm A']` Date format
skin : Usage is `[jclocksgmt skin=1]` Set 1 of 5 clock themes.


== Screenshots ==

1. Example of Clocks
2. Promotional Image

== Changelog ==

= 1.0 =
* Initial release
=== Contact Details by WooThemes ===
Contributors: jeffikus, woothemes
Tags: contact details, contact, maps, map, social media
Requires at least: 3.9
Tested up to: 3.9.1
Stable tag: 1.0.1
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Contact Details is a simple little plugin that will allow you to configure various contact details in the WordPress admin then display them on your web site.

== Description ==

= Contact Details =
Display various contact details including:

* Phone number
* Fax number
* Location name & address
* Email address

= Social Media =
Display links to your social media profiles on:

* Facebook
* Twitter

= Map =
Display a map of your address with a callout description.

Looking for a helping hand? [View plugin documentation](http://docs.woothemes.com/document/getting-started-with-contact-details/).

== Usage ==

Contact Details is the best plugin to get your users in touch with you!. You can use output the contact details in the following ways:

1. Add the template action into your themes php -> do_action( 'contact_details' );
2. Add the shortcode into the content of one of your posts or pages -> [contact_details]
3. Add the widget to a widget area -> Contact Details by WooThemes
4. Use the template tag in your themes php -> contact_details();

All output functions take the following arguments:
'display' with possible values of:
- 'all'
- 'details'
- 'social'
- 'map'

Shortcode Example:
1. Output a map
[contact_details display="map"]

== Installation ==

Installing "Contact Details by WooThemes" can be done either by searching for "Contact Details by WooThemes" via the "Plugins > Add New" screen in your WordPress dashboard, or by using the following steps:

1. Download the plugin via WordPress.org.
2. Upload the ZIP file through the "Plugins > Add New > Upload" screen in your WordPress dashboard.
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Visit the settings screen and configure, as desired.

== Frequently Asked Questions ==

= How do I contribute? =

We encourage everyone to contribute their ideas, thoughts and code snippets. This can be done by forking the [repository over at GitHub](http://github.com/woothemes/contact-details-by-woothemes/).

== Screenshots ==

1. The settings screen.


== Upgrade Notice ==

= 1.0.0 =
* 2014-06-05
* Initial release. Woo!

== Changelog ==

= 1.0.1 =
* 2014-07-17
* New - Added .pot file
* Tweak - Contact details markup

= 1.0.0 =
* 2014-06-05
* Initial release. Woo!

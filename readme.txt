=== Bible Link ===
Contributors: chaselivingston
Tags: bible, link, esv
Requires at least: 3.8.1
Tested up to: 4.0.0
Stable tag: 0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Bible Link uses a [bible] shortcode to parse Bible references and create links for them back to http://bible.com

== Description ==

Bible Link uses a `[bible]` shortcode to parse Bible references and create links for them back to http://bible.com. Currently it supports single verses only, and links to the ESV translation.

Usage example: `[bible]John 3:16[/bible]` would create a link to Bible.com that looks like https://www.bible.com/bible/esv/john.3.16.esv

Repo on GitHub: https://github.com/chaselivingston/biblelink

== Installation ==

1. Upload `biblelink.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Use the `[bible]Reference[/bible]` syntax in a post or a page to create the link, where Reference is a reference to a single Bible verse.

== Frequently Asked Questions ==

= How do I link books with numbers? =

Don't put a space between the number and book name. For example, `[bible]1Samuel 1:1[/bible]` will work, but not `[bible]1 Samuel 1:1[/bible]`.

= How do I use the shortcode? =

Example: `[bible]John 3:16[/bible]` would create a link to John 3:16 at http://bible.com.

== Screenshots ==

1. Editor view
2. Post view


== Changelog ==

= 0.1 =
* Initial version.

== Upgrade Notice ==

= 0.1 =
* Initial version.

=== NS Custom Fields for WordPress SEO ===
Contributors: neversettle
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RM625PKSQGCCY&rm=2
Tags: yoast, wordpress seo, seo, custom fields, acf
Requires at least: 3.3
Tested up to: 3.6
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Include content from custom fields in the Yoast WordPress SEO plugin's keyword analysis (WordPress SEO by Yoast is required).

== Description ==

Ever wanted to have your custom fields evaluated as part of the post's content in the Yoast WordPress SEO plugin's keyword statistics? With NS Custom Fields for Wordpress SEO, now you can!

For architecturally-advanced sites that use ACF (Advanced Custom Fields) or another post meta framework to store different parts of a post's content, WordPress SEO's usually-helpful keyword statistics can become skewed since they don't take keywords in all that custom field content into account.

With this plugin, you can specify up to 3 custom fields that you'd like to count as "content" (works for normal posts, pages AND custom post types!) when keyword scoring takes place. Say hello to accurate keyword statistics again.

If you want even more functionality, like support for ACF Repeater and Flexible Content fields, including custom fields in Yoast's automatic meta descriptions, or specifiying unlimited custom fields, [check out our Pro version!](https://neversettle.iljmp.com/1/ns-automation-for-wordpress-seo)

== Installation ==

1. Log in to your WordPress site as an administrator
2. Ensure that [WordPress SEO by Yoast](http://wordpress.org/plugins/wordpress-seo) is installed.
3. Use the built-in Plugins tools to install NS Cloner from the repository or Upload the ns-cloner directory to the /wp-content/plugins/ directory
4. Activate the plugin through the 'Plugins' menu in WordPress
5. Access the plugin settings in the admin menu via **SEO** > **Custom Fields Analysis**
6. Enter the post_meta key(s) of the custom field(s) you'd like to be included in content keyword scoring.

== Screenshots ==

1. Plugin settings page - easily control which custom fields you'd like to be included in the Yoast keyword analysis.
2. Diagram of where to find the right custom field names to use and where you'll see the updated keyword statistics. 

== Changelog ==

= 2.1.2 =
* Added custom field support to the live, at-a-glance keyword stats on the General tab of the Yoast metabox

= 2.1.1 =
* First public release

== Upgrade Notice ==


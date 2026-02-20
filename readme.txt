=== WP Sitemap Filter ===
Contributors: Michael Scheibl
Donate link: https://ko-fi.com/scheibl
Tags: sitemap, xml sitemap, seo, exclude, filter, wordpress sitemap
Requires at least: 5.5
Tested up to: 6.5
Stable tag: 3.5.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

A lightweight plugin to control which posts, pages, taxonomies and users appear in the WordPress core XML sitemap. Disable providers or exclude individual items.

== Description ==

WordPress includes a built‑in XML sitemap since version 5.5.  
However, it does not allow you to exclude individual posts, pages, categories, tags or users — nor does it allow disabling sitemap providers.

**WP Sitemap Filter** adds a simple and clean interface to:

* Exclude posts, pages, categories, tags or users
* Disable entire sitemap providers (posts, taxonomies, users)
* Keep all settings persistent across tabs
* View sitemap status directly in the admin area
* Access the sitemap URL with one click

This plugin is lightweight, fast and fully compatible with caching plugins.

== Installation ==

1. Upload the plugin folder to `/wp-content/plugins/`
2. Activate the plugin in the WordPress admin
3. Go to **WP Sitemap Filter** in the admin menu

== Frequently Asked Questions ==

= Does this replace the default WordPress sitemap? =
No. It extends and filters the existing core sitemap.

= Does it work with caching plugins? =
Yes. The sitemap is generated dynamically.

= Is this plugin GDPR compliant? =
Yes. It stores only local settings and does not send data to external services.

== Screenshots ==

1. Admin interface with filters
2. Provider settings
3. Sitemap status box

== Changelog ==

= 3.5.0 =
* Added sitemap status box (last update + sitemap URL)
* Improved persistence of provider settings
* Prepared GitHub auto‑update integration

= 3.4.0 =
* English UI and plugin header
* Initial public release

== Upgrade Notice ==

= 3.5.0 =
This update adds a status box and improves stability.

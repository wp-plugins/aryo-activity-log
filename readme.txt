=== Activity Log ===
Contributors: pojo.me, KingYes, ariel.k, maor
Tags: administration, activity, event, monitor, multisite, multi-users, log, logger, audit log, stats, security, tracking, woocommerce, notifications, email notifications
Requires at least: 3.5
Tested up to: 4.2
Stable tag: 2.2.1
License: GPLv2 or later

Get aware of any activities that are taking place on your dashboard! Imagine it like a black-box for your WordPress site.

== Description ==

<h3>Like being in control? Check this out.</h3>

We all know that it’s relatively easy to analyze what your visitors are looking for while browsing your site. But there is really no easy way to know what registered users (say, with an Administrator account or even Editors) are doing on the dashboard of your site. How can you know if a post was deleted? or if a plugin was activated/deactivated? or if the active theme was changed?
If you have tens of users or more, you really can’t know who did it. This plugin tries to solve this issue by tracking what users do on the dashboard of your WordPress site. 

<strong>As of this moment, the plugin logs things when:</strong><br />

* <strong>WordPress</strong> - Core Updates
* <strong>Posts</strong> - Created, Updated, Deleted
* <strong>Pages</strong> - Created, Updated, Deleted
* <strong>Custom Post Type</strong> - Created, Updated, Deleted
* <strong>Tags</strong> - Created, Edited, Deleted
* <strong>Categories</strong> - Created, Edited, Deleted
* <strong>Taxonomies</strong> - Created, Edited, Deleted
* <strong>Comments</strong> - Created, Approved, Unproved, Trashed, Untrashed, Spammed, Unspammed, Deleted
* <strong>Media</strong> - Uploaded, Edited, Deleted
* <strong>Users</strong> - Login, Logout, Login has failed, Update profile, Registered and Deleted
* <strong>Plugins</strong> - Installed, Updated, Activated, Deactivated, Changed
* <strong>Themes</strong> - Installed, Updated, Deleted, Activated, Changed (Editor and Customizer)
* <strong>Widgets</strong> - Added to a sidebar / Deleted from a sidebar, Order widgets
* <strong>Menus</strong> - A menu is being Created, Updated, Deleted
* <strong>Setting</strong> - General, Writing, Reading, Discussion, Media, Permalinks
* <strong>Options</strong> - Can be extend by east filter
* <strong>Export</strong> - User download export file from the site
* <strong>WooCommerce</strong> - Monitor all shop options
* <strong>bbPress</strong> - Forums, Topics, Replies, Taxonomies and other actions
* and much more...

<strong>New!</strong> You are now able to get email notifications once an event you have defined (via rules) has occured. This is useful in cases you must know right away when someone does something on your site.

<h4>What people are saying</h4>
* <em>“Best 10 Free WordPress Plugins of the Month – July 2014: Keeping tabs on what your users do with their access to the Dashboard”</em> - [ManageWp.com](https://managewp.com/best-free-wordpress-plugins-july-2014)
* <em>“Thanks to this step, we’ve discovered that our site was undergoing a brute force attack”</em> - [artdriver.com](http://www.artdriver.com/wordpress-site-hacked-solution-time/)
* <em>“Optimized code - The plugin itself is blazing fast and leaves almost no footprint on the server.”</em> - [freshtechtips.com](http://www.freshtechtips.com/2014/01/best-audit-trail-plugins-for-wordpress.html)
* <em>“The plugin successful for activity log for WordPress.”</em> - [wp-tricks.co.il](http://www.wp-tricks.co.il/2013/08/%D7%99%D7%95%D7%9E%D7%9F-%D7%A4%D7%A2%D7%99%D7%9C%D7%95%D7%AA-%D7%9C%D7%95%D7%95%D7%A8%D7%93%D7%A4%D7%A8%D7%A1-aryo-activity-log/)
* <em>“This is a pretty simple yet quite effective plugin for keeping track of what your admins and users do on your sites.”</em> - [shadowdragonunlimited.com](http://shadowdragonunlimited.com/plugin-of-the-week-9302013-aryo-activity-log/plugin-of-the-week/)

<h4>Translators:</h4>
* German (de_DE) - [Robert Harm](http://www.mapsmarker.com/)
* Dutch (nl_NL) - [Tom Aalbers](http://securancy.com/)
* Serbo-Croatian (sr_RS) - [Borisa Djuraskovic](http://www.webhostinghub.com/)
* Danish (da_DK) - [Morten Dalgaard Johansen](http://www.iosoftgame.com/)
* Hebrew (he_IL) + RTL Support - [Pojo.me](http://pojo.me/)
* Armenia (hy_AM) - Hayk Jomardyan
* Brazilian Portuguese (pt_BR) - [Criação de Sites](http://www.techload.com.br/criacao-de-sites-ribeirao-preto)
* Turkish (tr_TR) - [Ahmet Kolcu](http://ahmetkolcu.org)
* Persian (fa_IR) - [Promising](http://vwp.ir/)
* Russian (ru_RU) - Oleg Reznikov
* Polish (pl_PL) - Maciej Gryniuk

The plugin does not require any kind of setup. It works out of the box (and that’s why we love it too).

We’re planning to add a lot more features in the upcoming releases. If you think we’re missing something big time, please post your suggestions in the plugin’s forum.

<strong>Contributions:</strong><br />

Would you like to like to contribute to Activity Log? You are more than welcome to submit your pull requests on the [GitHub repo](https://github.com/KingYes/wordpress-aryo-activity-log). Also, if you have any notes about the code, please open a ticket on ths issue tracker.


== Installation ==

1. Upload plugin files to your plugins folder, or install using WordPress' built-in Add New Plugin installer
1. Activate the plugin
1. Go to the plugin page (under Dashboard > Activity Log)

== Screenshots ==

1. The log viewer page
2. The settings page
3. Screen Options
4. Interface for defining notification rules

== Frequently Asked Questions ==

= Requirements =
* __Requires PHP5__ for list management functionality.

= What is the plugin license? =

* This plugin is released under a GPL license.


== Changelog ==

= 2.2.1 =
* Fixes from prev release

= 2.2.0 =
* New! - Adds search box, to allow users to search the description field.
* New! - Allows users to now filter by action
* New! - Added translate: Polish (pl_PL) - Thanks to Maciej Gryniuk
* Tweak! - SQL Optimizations for larger sites

= 2.1.16 =
* New! Added translate: Russian (ru_RU) - Thanks to Oleg Reznikov
* Fixes Undefined property with some 3td party themes/plugins
* Tested up to WordPress v4.2

= 2.1.15 =
* Tested up to WordPress v4.1
* Change plugin name to "Activity Log"

= 2.1.14 =
* New! Added translate: Persian (fa_IR) - Thanks to [Promising](http://vwp.ir/)

= 2.1.13 =
* New! Added filter by User Roles ([#67](https://github.com/KingYes/wordpress-aryo-activity-log/issues/67))

= 2.1.12 =
* New! Added translate: Turkish (tr_TR) - Thanks to [Ahmet Kolcu](http://ahmetkolcu.org/)

= 2.1.11 =
* Fixed! Compatible for old WP version

= 2.1.10 =
* New! Now tracking when menus created and deleted
* New! Added translate: Portuguese (pt_BR) - Thanks to [Criação de Sites](http://www.techload.com.br/criacao-de-sites-ribeirao-preto)

= 2.1.9 =
* New! Store all WooCommerce settings ([#62](https://github.com/KingYes/wordpress-aryo-activity-log/issues/62))
* Tested up to WordPress v4.0

= 2.1.8 =
* New! Now tracking when plugins installed and updated ([#59](https://github.com/KingYes/wordpress-aryo-activity-log/pull/59) and [#43](https://github.com/KingYes/wordpress-aryo-activity-log/issues/43))

= 2.1.7 =
* New! Now tracking when user download export file from the site ([#58](https://github.com/KingYes/wordpress-aryo-activity-log/issues/58) and [#63](https://github.com/KingYes/wordpress-aryo-activity-log/pull/63))

= 2.1.6 =
* Tested up to WordPress v3.9.2

= 2.1.5 =
* New! Now tracking when theme installed, updated, deleted ([#44](https://github.com/KingYes/wordpress-aryo-activity-log/issues/44))

= 2.1.4 =
* Fixed! Store real IP address in Proxy too ([#53](https://github.com/KingYes/wordpress-aryo-activity-log/issues/53))

= 2.1.3 =
* New! Added translate: Dutch (nl_NL) - Thanks to [Tom Aalbers](http://securancy.com/) ([#55](https://github.com/KingYes/wordpress-aryo-activity-log/issues/55))

= 2.1.2 =
* Tweak! Update translate: Hebrew (he_IL)

= 2.1.1 =
* New! Track about WordPress core update (manual or auto-updated) ([#41](https://github.com/KingYes/wordpress-aryo-activity-log/issues/41))
* New! Track post comments (created, approved, unproved, trashed, untrashed, spammed, unspammed, deleted) ([#42](https://github.com/KingYes/wordpress-aryo-activity-log/issues/42))

= 2.1.0 =
* New! Personally-tailored notifications that can be triggered by various types of events, users and action type (currently only email notifications are supported)
* Bug fixes, stability improvements
* Fixed an error that occurred on PHP 5.5

= 2.0.7 =
* Tested up to WordPress v3.9.0

= 2.0.6 =
* Fixed! Random fatal error ([topic](https://github.com/KingYes/wordpress-aryo-activity-log/issues/32))

= 2.0.5 =
* New! Register `aal_init_caps` filter.
* Tweak! Change all methods to non-static.
* Tweak! Some improved coding standards and PHPDoc.
* Tweak! Split `AAL_Hooks` class to multiple classes.
* New! Added translate: Armenia (hy_AM) - Thanks to Hayk Jomardyan.

= 2.0.4 =
* Tweak! Don't allowed to access in direct files.
* New! Added translate: Danish (da_DK) - Thanks to [Morten Dalgaard Johansen](http://www.iosoftgame.com/)

= 2.0.3 =
* New! Record when widgets change orders.

= 2.0.2 =
* New! Save more Options:
* General
* Writing
* Reading
* Discussion
* Media
* Permalinks

= 2.0.1 =
* New! filter for disable erase all the log
* Bugs fixed

= 2.0.0 =
* Added Screen Options
* New! Ability to select a number of activity items per page
* New! Columns are now sortable
* Added filter by date - All Time, Today, Yesterday, Week, Month
* Added Avatar to author
* Added role for author
* Added log for activeted theme
* Re-order Culoumns
* Compatible up to 3.8.1
* Settings page is now accessible directly from Activity Log's menu
* Keep your log for any time your wants
* Delete Log Activities from Database.
* Bugs fixed


= 1.0.8 =
* Added translate: Serbo-Croatian (sr_RS) - Thanks to [Borisa Djuraskovic](http://www.webhostinghub.com/).

= 1.0.7 =
* Added 'view_all_aryo_activity_log' user capability ([topic](http://wordpress.org/support/topic/capability-to-access-the-activity-log)).

= 1.0.6 =
* Added WooCommerce integration (very basic).
* Added Settings link in plugins page.

= 1.0.5 =
* Fix - Make sure no save double lines (menu taxonomy / post).

= 1.0.4 =
* Added Taxonomy type (created, updated, deleted).

= 1.0.3 =
* Added Multisite compatibility.
* Added Options hooks (limit list, you can extend by simple filter).
* Added Menu hooks.
* Tweak - Ensure no duplicate logs.. 

= 1.0.2 =
* Forget remove old .pot file

= 1.0.1 =
* Added translate: German (de_DE) - Thanks to [Robert Harm](http://www.mapsmarker.com/)
* Added translate: Hebrew (he_IL)
* Plugin name instead of file name on activation/deactivation
* <strong>New Hooks:</strong>
* A widget is being deleted from a sidebar
* A plugin is being changed
* Theme Customizer (Thanks to Ohad Raz)

= 1.0 =
* Blastoff!

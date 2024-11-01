=== WP Network Stats ===
Contributors: harshit_ps
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=8764J82HE2VBN&lc=US&item_name=Harshit%20Sanghvi&item_number=wp_network_stats&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted
Tags: stats, network, site, plugin, theme, user, multisite, d3, visualization, batch, processing, cron, csv, export, notification, statistics, metrics, data
Requires at least: 4.0
Tested up to: 4.6
Stable tag: 1.0.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

View/Export network statistics related to users & plugins per site, themes, plugins and other site stats in your multisite network.

== Description ==

View/Export useful network statistics related to sites, users per site, plugins per site, themes and plugins for all the sites in a WordPress multisite network.

The features include -

1. Background processing for generating new statistics for the network. It allows you to safely generate stats without compromising the performance of your large multisite network.
2. Ability to fine tune batch processing settings.
3. Protected network admin settings.
4. Notification when the stats are available.
5. D3 Visualizations
6. Generates set of CSV files corresponding to different types of stats.

== Installation ==

= From your WordPress dashboard =

1. Visit 'Plugins > Add New'
2. Search for 'WP Network Stats' and click `Install`
3. Network Activate `WP Network Stats` from your Plugins page.

= From WordPress.org =

1. Download wp-network-stats.
2. Upload the 'wp-network-stats' directory to your '/wp-content/plugins/' directory, using your favorite method (ftp, sftp, scp, etc...)
3. In the WordPress Network Admin dashboard, navigation to the *Plugins* page, Locate the menu item that reads “WP Network Stats
4. Click on *Network Activate.*

= Installing a zip file =

1. Create a zip of `wp-network-stats` directory.
2. In the WordPress dashboard, navigate to the *Plugins* -> *Add New* page.
3. Click Upload Plugin.
4. Upload the zip file and click Install Now.
5. Click on *Network Activate.*

= Copying a Directory =

1. Copy the `wp-network-stats` directory into your `wp-content/plugins` directory.
2. In the WordPress Network Admin dashboard, navigation to the *Plugins* page and Locate the menu item that reads “WP Network Stats.
3. Click on *Network Activate.* 

== Frequently Asked Questions ==

= How can I contribute? =

Make Pull requests to github repository.

== Screenshots ==

1. Requesting latest Network Stats.
2. Cancel previous request for network stats and generate fresh stats.
3. Settings page for Network Stats.
4. Analytics - Users Registered (All time)
5. Analytics - Users Registered (Selected time)
6. Analytics - Sites Registered (All time)
7. Analytics - Sites Privacy
8. Analytics - Active Theme
9. Analytics - DB Version
10. Analytics - Multidimensional Detective
11. Analytics - Export selected data
15. Email notification with network stats overview and requested stats' attachments.
16. Stats - Plugins
17. Stats (Header only) - Users
18. Stats (Header only) - Themes
19. Stats (Header only) - Sites-1
20. Stats (Header only) - Sites-2
21. Stats (Header only) - Sites-3
22. Stats - User Stats Per Site
23. Stats - Plugin Stats Per Site


== Changelog ==
= 1.0.4 =
* Fixing previous SVN release

= 1.0.3 =
* New analytics charts
* New plugin stats using wordpress plugins api
* Secure csv file download for users with permissions only.
* Option to export selected data.
* Using bootstrap now on analytics page.

= 1.0.2 =
* Bug fix

= 1.0.1 =
* Bug fix

= 1.0.0 =
* Bug Fixes
* D3 Visualizations
* network menus and more settings
* more validations
* Background processing using cron job
* export to csv
* email notification

= 0.2.0 =
* Shows plugin stats.

= 0.1.0 =
* Shows site stats.

= 0.0.1 =
* This version has boilerplate code for the plugin.

== Upgrade Notice ==

= 1.0.0 =
Lots of new features

= 0.1.0 =
Upgrade to make this plugin actually do something.

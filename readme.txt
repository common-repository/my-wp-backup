=== My WP Backup ===
Contributors: mythemeshop
Creator's website link: http://mythemeshop.com/plugins/my-wp-backup/
Tags: backup, backups, restore, dropbox backup, google drive backup, ftp backup, back up, multisite backup, restoration, sftp backup, migrate, mysql backup, database backup, db backups, website backup, wordpress backup, full backup
Requires at least: 3.0.1
Tested up to: 5.0.0
Stable tag: 1.3.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

My WP Backup is the best way to protect your website in the event of server loss, data corruption, hacking or to migrate your WordPress data easily.

== Description ==

My WP Backup is the best way to protect your data and website in the event of adverse server events, data corruption, hacking and more. With the option to create whole site backups or database backups and have them **delivered via FTP, Dropbox, and Google Drive**, you can sleep easy knowing you're protected.

**90% of businesses that suffer a data loss are forced to close within 2 years.**

Website downtime can be incredibly costly for an online business. Not only does it result in loss in revenues from advertising or clients, but it also destroys user trust in your website and loss of visitors, and a reduced impression of your business.

In addition to that, over 30,000 websites are hacked every day, which can result in loss or corruption of data!

The solution? **<a href="https://mythemeshop.com/plugins/my-wp-backup/">My WP Backup</a>**!

100% of businesses and websites that use My WP Backup have avoided permanent data destruction and loss to their business, and have been able to focus on content creation as opposed to manual backups and technological stress.

Checkout <a href="http://demo.mythemeshop.com/s/?theme=My%20WP%20Backup%20Pro">Plugin Demo here</a>.

= Why My WP Backup from <a href="http://mythemeshop.com">MyThemeShop</a>: =

* Plugin Walkthrough
* Easy to Use
* Unlimited Backups
* Complete Backup Option
* Database Backup
* Themes Backup
* Plugins Backup
* Media Backup
* Split Backups into Volumes
* Restore Backups
* Backup on same server
* Backup to FTP
* Backup to Dropbox
* Backup to Google Drive
* ZIP Option for Archives
* Different Tar Archive Options
* Exclude Unnecessary Files
* Exclude Files with Globbing
* Get Notified via Email
* Low Memory Footprint
* Import/Export Settings
* Access to Logs
* Translation Ready
* 24/7/365 Support

= Support =

All support for this plugin is provided through our forums. If you have not registered yet, you can do so here for **FREE** <br>
<a href=“https://mythemeshop.com/#signup”>https://mythemeshop.com/#signup</a>

If after checking our Free WordPress video tutorials here:<br>
<a href=“https://mythemeshop.com/wordpress-101/”>https://mythemeshop.com/wordpress-101/</a><br>
&<br>
<a href=“https://community.mythemeshop.com/tutorials/category/2-free-video-tutorials/“>https://community.mythemeshop.com/tutorials/category/2-free-video-tutorials/</a><br>
<br>
you are still stuck, please feel free to open a new thread, and a member of our support team will be happy to help.<br>

Support link:<br>
<a href=“https://community.mythemeshop.com/forum/11-free-plugin-support/”>https://community.mythemeshop.com/forum/11-free-plugin-support/</a><br>
<br>

= Feedback =
If you like this plugin, then please leave us a good rating and review.<br> Consider following us on <a rel="author" href="https://plus.google.com/+Mythemeshop/">Google+</a>, <a href="https://twitter.com/MyThemeShopTeam">Twitter</a>, and <a href="https://www.facebook.com/MyThemeShop">Facebook</a>

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload the `my-wp-backup` folder to the to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. 'My WP Backup' Option will be available in Backend
4. Create new Backup Job and relax!

== Frequently Asked Questions ==

= Backup is not working =

Please disable all plugins and check if backup is working properly. Then you can enable all plugins one by one to find out which plugin is conflicting with WP Backup plugin.

== Screenshots ==

1. Welcome Screen
2. Plugin Tour
3. List Backups
4. List Backup Jobs
5. Global Settings
6. Single Job Settings
7. Backup Destination
8. Backup Report
9. Backup Log

== Changelog ==

= 1.3.7 =
* Updated admin notices

= 1.3.6 =
* Changed admin notices

= 1.3.5 =
* Update Google Drive client details

= 1.3.4 =
* Fix notice showing in backups table
* Fix 1.3.2 to 1.3.3 upgrade causing fatal error

= 1.3.3 =
* Add notice for pre-5.3 PHP users

= 1.3.2 =
* Improve: Faulty import/export option
* Fix: Missing lines while viewing backup job progress
* Minor improvements and optimizations

= 1.3.1 =
* Fix: Database gets corrupted when import fails
* Fix: Backup restore job duration was negative
* Fix: Job not showing "Finished" when it fails
* Improve: More helpful messages on failed database import
* Fix: Skip directory scan when backing up only the database
* Fix: Memory exhausted on testing exclude filters
* Improve: Database export
* Improve: Set error log for easier debugging
* Minor improvements and optimizations

= 1.3.0 =
* New: Add option to delete local backup copy
* Fix: Support custom database port and socket host
* Fix: Wrong job duration when job fails
* Fix: unclear instructions on connecting accounts from services
* Minor improvements and optimizations

= 1.2.0 =
* Fix: Completely remove Phar class usage
* Fix: Remove 64bit PHP requirement
* Fix: Cleanup created backup directory if the backup job fails
* Fix: chunked upload size might exceed the memory limit
* New: setting "Upload Size" to change the size of each chunk when chunk uploading
* Minor improvements and optimizations

= 1.1.2 =
* Fix: Backup gets accidentally deleted when restoration fails.

= 1.1.1 =
* Fix: Prevent direct access on some files
* Fix: Jobs and settings are now not deleted when the plugin is deactivated
* Fix: Wrong path being deleted when deleting the full archive after restoring a multi-volume backup
* Fix: Check if pcntl_signal is avaiable on wp-cli job command
* Fix: Change method of splitting new line
* Minor improvement on google drive and ftp upload
* Fix: Job options made compatible for upgrading to the pro version
* Added notification for pro version
* Fix: Jobs and settings being reverted to default when re-activating the plugin
* Removed: unnecessary languages/default.mo file
* Fix: Job fails on DB_HOST with custom port specified

= 1.1 =
* Added Compatibility with PHP v5.3.3
* Fixed: redirect to plugin dashboard on activation
* Fixed: database file not deleted after backup restore
* Fixed: Make sure backup directory is created
* Minor bug fixes and improvements

= 1.0.1 =
* Check PHP version requirement on plugin activation.

= 1.0 =
* Official plugin release.

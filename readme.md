# Modify wp-Admin.php

    Contributors:      Neel G Patel, WPOne.Tools, WPServices.Me
    Tags:              Modify WP-Admin, Modify WP-Login, Change WP-Admin, Remove WP-Admin, Remove WP-Login, Rename Wp-Admin, Rename Wp-Login, Change Admin URI, Change Login URI,
    Requires at least: 5.2
    Tested up to:      5.2
    Stable tag:        1.2.10
    License:           GPL-2.0+
    License URI: https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt

Do You Want to Change Your WordPress WP-Admin.PHP or wp-admin.php URI Fast & Safe Way Then Download Modify WP-Admin.PHP Today!

## Description
**I offer support throught the support form. use [WPOne] (https://www.wpone.tools/help)**

*Modify wp-admin.php* is a very small plugin that lets you easily and safely edit your wp-admin.php to anything you want. It doesn’t literally Modify or change files in core, nor does it add rewrite rules.

**Need More Information About Modify WP-Admin.PHP [WPOne](https://www.wpone.tools/plugins)**

## Compatibility

All login related things such as the registration form, lost password form, login widget and expired sessions just keep working.

It’s also compatible with any plugin that hooks in the login form, including

* BuddyPress,
* Woocommerce User Login,
* TML,
* bbPress,
* Limit Login Attempts,
* and User Switching.

Obviously it doesn’t work with plugins that *hardcoded* wp-admin.php.

Works with multisite, but not tested with subdomains. Activating it for a network allows you to set a networkwide default. Individual sites can still Modify their login page to something else.

If you’re using a **page caching plugin** you should add the slug of the new login url to the list of pages not to cache.

If you wish, you can block wp-admin.php with `.htaccess` from now on.

## Installation

1. Go to Plugins › Add New.
2. Search for *Modify wp-admin.php*.
3. Look for this plugin, download and activate it.
4. The page will redirect you to the settings. Modify wp-admin.php there.
5. You can change this option any time you want, just go back to Settings › Permalinks › Modify wp-admin.php.

## Frequently Asked Questions

### I forgot my login url!

Either go to your MySQL database and look for the value of `rwl_page` in the options table, or remove the `Modify-wp-login` folder from your `plugins` folder, log in through wp-admin.php and reinstall the plugin.

On a multisite install the `rwl_page` option will be in the sitemeta table, if there is no such option in the options table.

## Changelog

### 1.2.10
* Bug Fixes And Improvements
* Add Missing Element

### 1.1.10

* Initial Version.

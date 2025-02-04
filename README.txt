=== Eighty/20 Results - Single Use Trial for Paid Memberships Pro ===
Contributors: eighty20results
Tags: customizations, memberships, paid memberships pro, trial membership, single use trial membership
Requires at least: 3.9
Tested up to: 5.4
Stable tag: 2.0

Limit a member to sign up for a trial level once.

== Description ==
This plugin requires the Paid Memberships Pro plugin by Stranger Studios, LLC.

The plugin will prevent a single user ID (member) from signing up to a membership level more than once.

WARNING: There are ways for a member to bypass this setting. The simplest workaround is to register as a new user
on your site during the checkout process. Unfortunately, there is no fool-proof way to disable this workaround.

== Installation ==

1. Upload the `e20r-single-use-trial` directory to the `/wp-content/plugins/` directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Configure via the "Memberships" -> "Membership Levels" settings page, under the "Single Use Trial Settings" section for each level.

= Changelog =

== 2.0 ==

* ENHANCEMENT: Use the E20R Utilities module for sanitizing REQUEST variables
* ENHANCEMENT: Use the E20R Utilities module to handle plugin update logic
* ENHANCEMENT: Updated copyright notice

== 1.2 ==

* BUG/ENHANCEMENT: Expanded to allow single-use configuration for any membership type, not just free levels.

== 1.1 ==

* ENH/BUG: Added custom boolval() for ancient versions of PHP

== 1.0.4 ==

* ENH: Add GPL v2 license text to source file.
* ENH: Add descriptive text to settings section on Membership Level definition page

== 1.0.3 ==

* BUG: Didn't always load settings on page

== 1.0.2 ==

* BUG/ENH: Make e20r_force_tls_12() pluggable
* ENH: Add header text to settings page

== 1.0.1 ==

* Adding debug capabilities

== 1.0 ==

* Initial Release of the add-on

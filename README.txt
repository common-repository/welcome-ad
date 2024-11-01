=== Simple Welcome Ad ===
Contributors: mattpramschufer, emoxie
Tags: Welcome Ad, welcome mat, welcome popup, interstitial, Prestitial
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=mattpram%40gmail%2ecom
Requires at least: 3.8
Requires PHP: 5.6
Tested up to: 5.8
Stable tag: 1.5.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Super simple welcome ad that adheres to the new Google Ad Experience guidelines.

== Description ==
This is a super simple plugin which displays a full page welcome ad for visitors.   I created this plugin out of necessity as I needed a welcome ad plugin that would adhere the new Google Ad Experience guidelines for interstitial ads.  The requirements state that no content can be visible to a user before your interstitial appears, that means even if your content flashes for a split second before your ad shows your site will not pass.

Like the title of the plugin says, this is super simple.  The welcome ad has only a few options, feel free to request new features and I can try to incorporate.

The welcome ad is designed to NOT show on mobile devices only Desktops.

== Features ==

* Only displays on Desktop
* Adjustable Second Countdown Timer
* Set how long you want ad to be hidden for after someone closes ad
* Ability to upload background image
* Ability to change color of welcome ad background
* NEW Ability to schedule start date and end date for welcome ad to run.

== Installation ==
1. Activate the plugin through the `Plugins` menu in WordPress
1. Browse through the Welcome Ad settings and enable ad


== Frequently Asked Questions ==

= I really wish this plugin did XYZ, can you implement =

More than likely!  Feel free to contact me and suggest features and I will do my best to incorporate in.

= Do you offer support? =

Yes, I do the absolute best I can to support the free version of the plugin.

== Screenshots ==

1. Settings Screen
2. Welcome Ad

== Changelog ==

= 1.5.0 =
* UPDATE - Updated all vendor libraries

= 1.4.4 =
* BUG FIX - Addressed issue where when running WP Rocket caching plugin, welcome ad would fire two times before staying hidden.
* UPDATE - Updated all vendor libraries

= 1.4.3 =
* BUG FIX - Corrected issue with latest version of chrome and e.preventDefault()
* PATCH - Added in a patch for folks using ConvertPro Exit Pop plugin
* UPDATE - Refactored javascript to load faster

= 1.4.2 =
* BUG FIX - Fixed issue with welcome ad html being displayed on RSS feeds

= 1.4.1 =
* Added in ability to specify countdown time
* Added in WP Rocket caching support

= 1.4.0 =
* Complete rewrite of codebase

= 1.3.1 =
* Complete roll back

= 1.2.0 =
* Added in ability to allow for scheduling of the popup

= 1.1.0 =
* Initial Release

== Upgrade Notice ==
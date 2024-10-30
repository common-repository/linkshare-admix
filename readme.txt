=== LinkShare AdMix ===
Contributors: Peter Wayner 
Donate link: http://projects.radgeek.com/feedwordpress/
Tags: affiliate marketing, widget, links, ads, Linkshare, rss, atom, feed, syndication, aggregation 
Requires at least: 2.7
Tested up to: 3.4.1
Stable tag: 0.1

LinkShare AdMix gathers new deals from LinkShare's RSS feeds and mixes
them into your blog.


== Description ==

* Author: [Peter Wayner]
* Project URI: <http://www.linkshare.com/>
* License: GPL 2. See License below for copyright jots and tittles.

LinkShare AdMix is based upon the work of Charles Johnson (http://radgeek.com/contact). The latest version is supported by LinkShare. To ask for support or suggest improvements, contact developers (at) linkshare.com.

LinkShare AdMix makes it easy for you to integrate RSS content ads from LinkShare Advertisers with your blog posts.  Simply choose the feeds you'd like to promote, and then subscribe to them in your WordPress Admin area.  

LinkShare RSS AdMix uses RSS feeds from LinkShare Advertisers to populate your Wordpress blog with deals and other promotional content. You can earn a commission on every sale on an Advertiser site that your blog refers.   You can also promote feeds from multiple Advertisers at the same time.  

IMPORTANT - Please note that you'll need to join the LinkShare Network and be approved into an Advertisers affiliate program in order to display the feed and earn a commission on sales.



  [2.5]: http://codex.wordpress.org/Version_2.5
  [2.3]: http://codex.wordpress.org/Version_2.3
  [2.2]: http://codex.wordpress.org/Version_2.2
  [2.1]: http://codex.wordpress.org/Version_2.1
  [2.0]: http://codex.wordpress.org/Version_2.0
  [1.5]: http://codex.wordpress.org/Version_1.5

== Installation ==

*	Download the zip file for the AdMix plug-in
*	Unzip the downloaded package and upload the plug-in folder into your Wordpress plug-ins folder at wp-content/plugins 
*	Optional - Some older versions of WordPress have trouble parsing certain feeds. You can upgrade your version by replacing rss.php and rss-functions.php in your wp-includes directory with the new versions in this distribution.
*	Log into your Wordpress admin panel
*	Go to Plug-ins and activate the LinkShare AdMix plug-in
*	Once the plug-in is activated, you can go to LinkShare AdMix --> Options and set (1) the link category that FeedWordPress will syndicate links from (by default, "Contributors"), and (2) whether FeedWordPress will use automatic updates or only manual updates
*	Go to the main LinkShare AdMix page
*	Enter your feed token
*	Choose which Advertiser feeds you'd like to display in AdMix



== Using and Customizing LinkShare AdMix ==

You can choose the RSS feeds that will be added to your blog in the administration
Dashboard. 

== Frequently Asked Questions ==


= Where do I go to join LinkShare? =
Sign up at https://cli.linksynergy.com/cli/publisher/registration/registration.php

= How do I partner with Advertisers? =
Once you're in the LinkShare Network, navigate through the Programs tab to find Advertisers to partner with. It's a good idea to first install the plug-in and find which Advertisers offer RSS feeds you'd like to promote and then apply to their programs. 

= Where do I find my "token"? =
In the Publisher Dashboard at http://cli.linksynergy.com/cli/publisher/links/webServices.php

= Do all LinkShare Advertisers offer RSS feeds? =
No, only certain Advertisers offer feeds. 

= Do I need to continually update my plug-in? =
No! The plug-in is powered by RSS feeds that are continually updated :with new content at the Advertisers discretion. 

You'll find a comprehensive Publisher help center at http://helpcenter.linkshare.com/publisher. 

= Can you tell us about the provenance of the work? =
Yes, we grabbed the feedwordpress plugin from Charles Johnson tweaked it to work with Linkshare's RSS feeds. This is also released with the GPL license.

= Why am I getting a 'fatal error' message? =
The plugin needs to know where to put the adds.  You need to copy `<?php get_linkshareRSS(); ?>` into your theme somewhere. I often use the sidebar.php file.
 

= Where can I preview my feeds? =
http://cli.linksynergy.com/cli/publisher/links/dataFeeds.php?subpage=RSS

= How can I contact you? =
Write us at developers (at) linkshare.com 


== License ==

The LinkShare AdMix uses
code derived or translated from:

-  [feedwordpress.php][] by [Charles Johnson]()
-  [wp-rss-aggregate.php][] by [Kellan Elliot-McCrea](kellan@protest.net)
-  [MagpieRSS][] by [Kellan Elliot-McCrea](kellan@protest.net)
-  [HTTP Navigator 2][] by [Keyvan Minoukadeh](keyvan@k1m.com)
-  [Ultra-Liberal Feed Finder][] by [Mark Pilgrim](mark@diveintomark.org)

according to the terms of the [GNU General Public License][].

This program is free software; you can redistribute it and/or modify it under
the terms of the [GNU General Public License][] as published by the Free
Software Foundation; either version 2 of the License, or (at your option) any
later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.
n
  [wp-rss-aggregate.php]: http://laughingmeme.org/archives/002203.html
  [MagpieRSS]: http://magpierss.sourceforge.net/
  [HTTP Navigator 2]: http://www.keyvan.net/2004/11/16/http-navigator/
  [Ultra-Liberal Feed Finder]: http://diveintomark.org/projects/feed_finder/

  [GNU General Public License]: http://www.gnu.org/copyleft/gpl.html


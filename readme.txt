=== Juicer ===
Contributors: weckersham
Tags: social media feed, social media analytics, social media embed, social media aggregator, social media embed, embed social media, social hub, social, media, aggregate, aggregator, Facebook, Twitter, Instagram, YouTube, Google Plus, Tumblr, Pinterest, Vine, Soundcloud, RSS, autoblog, autoblogger, feed aggregator
Donate link: http://www.juicer.io
Requires at least: 3.0
Tested up to: 4.1
Stable tag: trunk
License: GPLv2

== Description ==
Juicer is a service that allows you to enter in the name of your social media accounts (or, if you prefer, hashtags) and Juicer will automatically pull the posts from these feeds and embed them into any of your pages with an easy shortcode. Juicer will automatically update these feeds whenever you create posts for your social media accounts.

To use this plugin you must create an account on [http://www.juicer.io](http://www.juicer.io). Then you must create a feed and add social media sources to it.

= Features =

* A beautiful feed of your social media content from basically networks: Facebook, Twitter, Instagram, YouTube, Google Plus, Tumblr, Pinterest, Tumblr, Vine, and RSS.
* Gather your content by @username or #hashtag
* Setup rules & filters to automatically eliminate unwanted content retweets and duplicate posts.
* Moderate and remove your social media content with one click.
* Permalinks to each of your social media posts, optimized for SEO.
* Responsive grid for dynamic layouts.
* Infinite scroll: load more content simply by scrolling to the bottom of the page.
* Auto-approve all your user generated content, or set up auto-moderation filters.
* Custom CSS: Style it to fit your brand or site.
* Advanced Analytics: Find out who uses your social feed, and how they interact with it.

Visit [http://www.juicer.io](http://www.juicer.io) for more information

== Installation ==
Download the plugin zip file, unzip it, and upload it to your wordpress site under the /wp-includes/plugins directory.

Sign up via [http://www.juicer.io](http://www.juicer.io) and create a feed for free

One you've done that you can use the shortcode: `[juicer name='YOUR_FEED_NAME' columns='3']` in any post or page

To get your Juicer feed name:

- Sign into your account on http://www.juicer.io
- Navigate to http://www.juicer.io/feeds
- Click "Edit" on the feed you wish to embed
- You should be taken to a url like http://www.juicer.io/feeds/example-feed
- The 'example-feed' portion of the url is your feed name.
- To use a shortcode for the embed feed try `[juicer name='example-feed' columns='2']`

Alternately, you can add the feed to your template directly if you like using PHP. Here's an example: `<?php juicer_feed('name=juicer&columns=3); ?>`

== Frequently Asked Questions ==

= What is Juicer? =
[Juicer](http://www.juicer.io) is a service that allows you to create an embeddable feed of all your social media accounts. It's great for increasing brand awareness and engagment and for providing fresh and interesting content for your website with very little work. It auto updates every day, pulling in any new posts, so your feed will always be fresh with your latest social media posts.

= How much does it cost? =
Juicer is free forever. No really! There is a paid account that gives you added features like adding more social media accounts, creating multiple feeds and getting detailed social analytics. But if you just want a feed for your website, it's free forever!

= It's not working for me! =
Sorry to hear that! Give us a shout on our [Contact Page](http://www.juicer.io) and we'll help you out!

== Screenshots ==
1. An example Juicer Feed using a provided template
2. A Juicer feed with custom CSS
3. The Juicer Feed Edit with all the functionality you are able to use.

== Changelog ==
1.0.0 Initial Version

== Upgrade Notice ==
No problems should be encountered when upgrading.

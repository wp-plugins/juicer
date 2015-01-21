=== Juicer ===
Contributors: goddamnyouryan
Tags: social media feed, social media analytics, social media embed, social media aggregator, social media embed, embed social media, social hub, social, media, aggregate, aggregator, Facebook, Twitter, Instagram, YouTube, Google Plus, Tumblr, Pinterest, Vine, Soundcloud, RSS, autoblog, autoblogger, feed aggregator
Donate link: http://www.juicer.io
Requires at least: 3.0
Tested up to: 4.1
Stable tag: trunk
License: GPLv2

Juicer is a beautiful social media feed generator that you can embed on any page.

== Description ==
Juicer is a service that allows you to enter in the name of your social media accounts (or, if you prefer, hashtags) and Juicer will automatically pull the posts from these feeds and embed them into any of your pages with an easy shortcode. Juicer will automatically update these feeds whenever you create posts for your social media accounts.

To use this plugin you must create an account on http://www.juicer.io. Then you must create a feed and add social media sources to it.

A full list of all the social media sites Juicer supports:

- Facebook
- Twitter
- Instagram
- YouTube
- Google Plus
- Tumblr
- Pinterest
- Vine
- Soundcloud
- Any RSS feed

Juicer also includes tools such as moderation, custom css styling, and several pre-made beautiful themes. Paid accounts also include further features, such as more frequent feed updates, more advance moderation and filtering tools, non-branded feeds, analytics, and SSL support.

Visit http://www.juicer.io for more information

== Installation ==
Download the plugin zip file, unzip it, and upload it to your wordpress site under the /wp-includes/plugins directory.

Sign up via http://www.juicer.io and create a feed for free

One you've done that you can use the shortcode: [juicer name='YOUR_FEED_NAME' columns='3'] in any post or page

To get your Juicer feed name:

- Sign into your account on http://www.juicer.io
- Navigate to http://www.juicer.io/feeds
- Click "Edit" on the feed you wish to embed
- You should be taken to a url like http://www.juicer.io/feeds/example-feed
- The 'example-feed' portion of the url is your feed name.
- To use a shortcode for the embed feed try [juicer name='example-feed' columns='2']

Alternately, you can add the feed to your template directly if you like using PHP. Here's an example: <?php juicer_feed('name=juicer&columns=3); ?>

== Screenshots ==
1. http://i.imgur.com/MIoyLLU.jpg
2. http://i.imgur.com/1xq2ffG.jpg
3. http://i.imgur.com/tYEcUXo.jpg

== Changelog ==
1.0.0 Initial Version

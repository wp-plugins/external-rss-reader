=== Silencesoft RSS Reader ===
by: Byron Herrera - bh at silencesoft dot net
Contributors: silence
Donate link: http://www.silencesoft.net/
Tags: rss, password
Requires at least: 2.0.2
Tested up to: 2.8
Stable tag: 0.3

A plugin to read external rss feeds

== Description ==

Using Plugin:
---

Add it on a page:
[sil_rss:0:content:0]
* First Param: 0 - The total of items to show.
* Second Param: content - Type to show (content or widget).
* Third Param : 0 - Category to show.
Sample:
[sil_rss:5:widget:1] - Show 5 items of category 1 like widget.

Call function:
To show the list calling a function, use:
<?php echo sil_rss_show(20, "content", 0); ?>
Params are same like before.

List all blogs:
To show the list of all blogs on a page, use:
[sil_rss_list_blogs]
or call it by a function
<?php echo sil_rss_list_blogs(); ?>

RSS:
Your url to subscribe to RSS is:
your_url/?feed=external
Saving OPML:

Your OPML file exported is on:
your_url/?sil_opml


Thanks to
---
Autoritas Consulting, sponsors of this plugin. :)
<http://www.autoritas.es/>


== Installation ==

Upload plugin folder to plugins folder.
CHmod 777 cache and images folders.
Change Options as necesary.

== Changelog ==

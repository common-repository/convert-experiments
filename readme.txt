=== Convert Experiences ===
Contributors: claudiur
Tags: plugin, a/b test, a/b testing, conversion optimization, split testing, website, convert experiences, convert
Requires at least: 3.5.1
Tested up to: 6.5.2
Stable tag: 3.1.8
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html

Convert Experiences provides advanced A/B and MVT Testing functionality for your website or blog.

== Description ==

A/B testing for WordPress now possible and simple.
It will enable your WordPress installation for use with the Convert Experiences conversion optimization suite.

The plugin will automatically send the several details, including, but not limited to: page type, page name, category name, category ID, and tags to Convert Experiences.

A/B testing on any set of categories or pages is then easy with the advanced filtering and segmentation during test
configuration.

> You'll need a [Convert Experiences account](http://www.convert.com/pricing/) to use this plugin.  Once you have that,  A/B tests are easy to
> setup without any technical knowledge.

<h4>What does the plugin do?</h4>

At a high level, this plugins sole purpose is to quickly install a small block of javascript onto each page of your
WordPress installation. The installed javascript is necessary for the Convert Experiences suite to perform its
A/B, split URL and multivariate functionality on your blog.

With some slight variations (based on the type of page being viewed: home, single, category, tag, or page), the
inserted javascript will look like the following:

`<!-- begin Convert Experiments code-->
<script type="text/javascript" src="//cdn-4.convertexperiments.com/js/1-4.js"></script>
<!-- end Convert Experiments code -->`

== Installation ==
[Sign up on the Convert Experiences page](http://www.convert.com/pricing/).

1. Go to Plugins -> Add New -> Search for the plugin or upload the plugins zip file.
2. Activate the plugin.
3. Copy your Account ID and Project Number from the Project Settings on Convert App, go to your WP-Admin > Plugins > Installed Plugins > Convert Experiences >  Configuration Page and insert your account and project numbers on this format:

accountID_projectID (ex.: 1003483_1003984)

== Screenshots ==

01 Settings

== Changelog ==
= 3.1.8 =
* Using Latest tracking code
= 3.1.7 =
* Fixing PHP 8 issue
= 3.1.6 =
* Tracking scripts updated.
* New WP versions compatibility check.
= 3.1.5 =
* Labels fix.
= 3.1.4 =
* Bug fix.
= 3.1.3 =
* Screenshots updated.
= 3.1.2 =
* Fixed backend styles.
= 3.1.1 =
* Screenshots, instructions, tooltips and text fields updated. Tested and confirmed working on Wordpress release 5.5.3
= 3.0.4 =
* Bug fixes.
= 3.0.3 =
* Updating main plugin banner.

= 3.0.0 =
* Update plugin to use latest Convert Experiences tracking snippet.

= 2.0.1 =
* We forgot to delete an old file from SVN, causing the plugin to be two plugins in one.

= 2.0 =
* Yoast rewrote plugin logic for better development standards.
* Made the entire plugin i18n ready.

= 1.3 =
* Changing tracking code to a better and faster one that allows experiments to be triggered faster and tracked better.

= 1.2 =
* Fix limitation on number of characters the project code could have.

= 1.1 =
* Added post title, page title, and category names as 'product name'
* Escape single quotes in javascript text variables.
* Added image showing where to retrieve the Product Number from the Convert Experiments™ dashboard.

= 1.0 =
* Initial release.

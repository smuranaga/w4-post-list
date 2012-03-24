=== W4 post list ===
Plugin Name: W4 post list
Author: sajib1223, shazzad, Shazzad Hossain Khan, W4dev
Donate link: http://w4dev.com/w4-plugin/w4-post-list
Tags: posts, categories, post list, category list, custom post list
Requires at least: 3.0
Tested up to: 3.3.1
Stable tag: 1.5.7

With the w4 post list plugin you can show a list of selected posts, selected categories or a list with both of them on your WordPress site.

== Description ==
Show Posts / Category Posts list inside post/page content or widget areas by shortcodes. Select what to show and design how to show it. jQuery enabled with slide effect. For details <a href="http://w4dev.com/w4-plugin/w4-post-list/">visit plugin page</a>.

You will be using template tag for creating a custom design for your list. If you don't understand the perfect usage of this plugin template tags, then you won't be able to take much out of it. <a href="http://w4dev.com/wp/w4-post-list-design-template/">Visit here</a> to get plugin's template tag definition or for some examples.

= What's new on 1.5.7 =
* Template Tag Changed. Now use Template Tags as like WordPress Shortcode Wrapped With Third Brackets[].
* Simple Javascript bug fixed.


= Shortcode =
Use shortcode "postlist" to show your list inside post/page content area. Example: <code>[postlist 1]</code> will show the list having id "1".

= Understanding Post List Options =
* List ID: Current list id. This id is necessary for showing list with shortcode. You can show a post list on your post or page by list id. Example: [postlist 1] will show the list having id 1.
* List name: This is not very essential now. Just for finding a list with this name on post list page menu.
* List type: List type chooser. Only post list, only category list and both them together are available. Note: Selecting and saving this option will hide or reveal related option fields. So we recommend you do make a save after choosing your list type.
* Show posts in category with a jQuery slide effect: This is only for "Posts with categories" list type. Positive selection will create a show/hide effect with jQuery to your list.
* Post order by: In Which base the post will be orderby. Available options are newest, oldest, most popular, less popular, by alphabetic order (A-Z/Z-A) and random.
* Show future Posts: Automatically add future posts to the category post/only posts/only posts by category list or remove.
* Show item count appending to category name: Show the published posts number for the category.
* Read-more Text: The single page link text ( not title).

== Installation ==
1. Upload zip to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Find W4 post list menu under Posts Menu. Add and manage post list from there.
4. User shortcode [postlist] with id, or copy shortcode from the post list options page.

== Frequently Asked Questions ==
= Can i show post from any category ? =
Yes.

= How many category i can show ? =
As much as you have.

== Screenshots ==
1. A Basic Design template tag definition.
2. W4 Post List Examples

== Changelog ==
= 1.0 =
* Begin.
= 1.1 =
* Added multi widget functionality. So now you can use it multiple time on the widgets section.
* Added more options.
* Fixed bug for category count
= 1.2 =
* Fixed the excerpt bugs.
= 1.2.1 =
* Fixed category selection bugs
= 1.2.2 =
* Changed preview style and Added few features
= 1.2.3 =
* Changed the posts selection method on Version 1.2.3.
* Changed the preview style on Version 1.2.3.
= 1.2.4 =
* Fixed post list bugs.
= 1.2.5 =
* Show/hide post list with Sliding effect while showing posts with category
* Bug Fixed.
* Added new option to show last post-modified time.
= 1.2.7 =
* Enabled multilingual functionality.
= 1.3 =
* Show list also on inside post content, page content.
= 1.3.1 =
* Changed parameter to easily understand options. Please deactivate and reactive plugin after update if you face any problem.
* Added template tag to show a specific post list at any place of your theme.
= 1.3.2 =
* Easier post sorting options.
= 1.3.3 =
* Read more link after content.
* Jquery effects to manage the list option more easily.
* Changed post order by to an easier method.
* A new "post select by" option.
= 1.3.4 =
* Option Saving Bug fixed
= 1.3.6 =
* List only posts by category.
* Show/Not show future posts.
* Post lists with maximum posts to show.
* One click select/deselect all posts.
= 1.4 =
* Its been a total change in this version. New Management page added for Admins to assign capability for creating/managing post list. If a user has role to only create and manage his own list, he won't be able to see/edit/delete the rest of post list option page.
* Post list database management process. Admin can drop or install the plugin database on click. People are recommended to do removal and install old database once if they have upgraded to v.1.4 from a old once. When database table is dropped, plugin keeps the old data and prompt for synchronize it once after installation of plugin database table. Only admin can have this feature.
* HTML Design template. You can design you list HTML template. For instruction, follow <a href="http://w4dev.com/wp/w4-post-list-design-template/">http://w4dev.com/wp/w4-post-list-design-template/</a>
= 1.4.5 =
* The show future posts bug has been solved. From now on, there won't be any selecton problems.
* Sliding Javascript has been updated to match the latest jQuery.
= 1.4.6 =
* A lot more template tag to arrange your post list with more flexibility.
= 1.5 =
* Stable Version
= 1.5.1 =
* Post Comment Count and Comment url tag added.
* Fixed Html Template input issue.
= 1.5.3 =
* Category Post selection problem fixed.
= 1.5.4 =
* Include Post Thumbnail/Image in the list.
= 1.5.5 =
* Manage How to select the post image. Lots of options.
= 1.5.6 =
* Important Updates.
= 1.5.7 =
* Template Tag Changed.

== Upgrade Notice ==
= 1.0 =
= 1.1 =
* Please update to 1.1, to avoid the simple category count bug and enjoy the multi widget functionality.
= 1.2 =
* Please update to Version 1.2 for showing the actual excerpt length and removing it from other contents.
= 1.2.1 =
* Please update to Version 1.2.1 which fixed the category selection bugs from widget page
= 1.2.2 =
* Changed past preview style. Update for using new listing style.
= 1.2.3 =
* Changed the posts selection method.
* Changed the preview style.
= 1.2.4 =
* Fixed post list bugs.
= 1.2.5 =
* Show/hide post list with Sliding effect while showing posts with category
* Bug Fixed.
* Added new option to show last post-modified time.
= 1.2.7 =
* Enabled multi-lingual functionality.
= 1.3 =
* Show list also on inside post content, page content.
= 1.3.1 =
* Changed parameter to easily understand options. Please deactivate and reactive plugin after update if you face any problem.
* Added template tag to show a specific post list at any place of your theme.
= 1.3.2 =
* Easier post sorting options.
= 1.3.3 =
* Read more link after content.
* Jquery effects to manage the list option more easily.
* Changed post order by to an easier method.
* A new "post select by" option.
= 1.3.4 =
* Option Saving Bug fixed
= 1.3.6 =
* List only posts by category.
* Show/Not show future posts.
* Post lists with maximum posts to show.
* One click select/deselect all posts.
= 1.4 =
* Its been a total change in this version. New Management page added for Admins to assign capability for creating/managing post list. If a user has role to only create and manage his own list, he won't be able to see/edit/delete the rest of post list option page.
* Post list database management process. Admin can drop or install the plugin database on click. People are recommended to do removal and install old database once if they have upgraded to v.1.4 from a old once. When database table is dropped, plugin keeps the old data and prompt for synchronize it once after installation of plugin database table. Only admin can have this feature.
* HTML Design template. You can design you list HTML template. For instruction, follow <a href="http://w4dev.com/wp/w4-post-list-design-template/">http://w4dev.com/wp/w4-post-list-design-template/</a>
= 1.4.5 =
* The show future posts bug has been solved. From now on, there won't be any selection problems.
* Sliding JavaScript has been updated to match the latest jQuery.
= 1.4.6 =
* A lot more template tag to arrange your post list with more flexibility.
= 1.5 =
* Stable Version
= 1.5.1 =
* Post Comment Count and Comment url tag added.
* Fixed Html Template input issue.
= 1.5.3 =
* Category Post selection problem fixed.
= 1.5.4 =
* Include Post Thumbnail/Image in the list.
= 1.5.5 =
* Manage How to select the post image. Lots of options.
= 1.5.6 =
* Important Updates.
= 1.5.7 =
* Template Tag Changed.


== How to use ==

Visit <a href="http://w4dev.com/w4-plugin/w4-post-list/">Plugin page</a> for detail usage.

= General tags: =
* postlist -- You complete post list html.
* postloop -- Post Template Loop. While displaying posts, every post go through the postloop once.
* catloop == Category Template Loop. While displaying categories, every category go through the catloop once
Category tags:
* category_title -- Category title template
* category_count -- Category item count
* category_posts -- Posts inside this category. If you leave this field empty, And using post category list type, selected posts wont be visible

= Post tags =
* title -- Post title template
* Image -- Post Thumbnail/image template. You can stylize this image with "w4pl_post_thumb" css class
* meta -- Meta template. Ex: Posted on date by author
* publish/date -- Post publishing date template
* modified -- Post last update date template
* author -- Post author template linked to author url
* excerpt -- Post excerpt template
* post_excerpt -- Raw Post excerpt without wrapper. By default we wrap it with a html div
* content -- Post content template
* content -- Raw Post content without wrapper
* more -- Read more template

= More Post tags =
Visit <a href="http://w4dev.com/wp/w4-post-list-design-template/">plugin template definition page</a> for additional tags information.

= Using Template tag =
You can wrap a tag easily with your own html tags. Like: <span class="my-time">publish</span> while editing a list.
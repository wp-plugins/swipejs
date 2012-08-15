=== Plugin Name ===
Contributors:
Donate link: http://ohdoylerules.com/swipejs/
Tags: slider, swipe, touch, mobile, css3, transitions, responsive, slideshow
Requires at least: 2.0.2
Tested up to: 3.4.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Swipe.js is a small, touch-capable, mobile slider.

== Description ==

Swipe.js is a mobile, touch-capable slider framework built by [Brad Birdsall](http://www.twitter.com/BradBirdsall). The home page for the swipe project is <a href="http://swipejs.com/">swipejs.com</a>. This plugin adapts swipe.js for easier use in WordPress. Before, the slider would have to be built into a theme. Now it can be used on any page just by using the shortcode.

This plugin requires [css3 3d transform support](http://caniuse.com/#feat=transforms3d). If you browser version is in the red then this slider will not work. You will have to update to a more modern browser or switch browsers all together.

This project is also [hosted on Github](https://github.com/james2doyle/Swipe.js-WordPress-Plugin).

== Installation ==

1. Install the plugin, either through the WordPress plugin repository or install via zip file.
2. Create a new post under the SwipeJS post menu.
3. Give the post a title and a featured image.
4. Under the settings menu go to SwipeJS
5. Modify the settings to what you need.
6. Create a new page or add the shortcode `[sjs-slideshow]` to an existing page

== Frequently Asked Questions ==

= How can I edit the styling? =

There is a style.css file included in the plugin. There is a default style that can be overwritten. All of the CSS classes and IDs are in that stylesheet.

= My images are different heights =

Please format/crop your images to all be the same size. SwipeJS has no cropping or sizing.

= My newest slide is last =

That is proper. Add slide one first. All the posts are in ascending order. This means that the newest post will appear as the last image.

= The slider is broken or not working =

The slider uses CSS3 transitions and transforms to move the images. This means you will need a relatively new version of your browser. You can see a list of compatible browsers on [this chart](http://caniuse.com/#feat=transforms3d). Red means there is no support and green means full support. If your browser falls in the red zone, either update your browser or you may have to use a different slider.

== Screenshots ==

1. Default styling with pagination and controls enabled.

== Changelog ==

= 1.0 =
* Initial release.
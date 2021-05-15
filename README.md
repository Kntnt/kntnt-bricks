# Kntnt Bricks

Collections of files that gives WordPress an alternative way of building web pages.

## Description

Kntnt Bricks are pronounced “content bricks”. That is also what they are: Bricks of content that are placed on top of each other. Thus, bricks build the page from top to bottom.

Bricks consist of one, two or three boxes laid out from left to right. Boxes can contain nothing, text, image or text on image. Text colour can be either dark or light. Text background can be either transparent or coloured. Text on images can either have a shadow or a semitransparent layer beneath.

Bricks can either be narrow or wide, have their natural height or be limited by a min-height and/or a max-height. Boxes stack either normal or reverse on mobile units.

Some of all variations can be seen in [this demo](https://codepen.io/tbarregren/pen/bGgaNzm).

## Requirements

Kntnt Bricks builds on the pure CSS project [Kntnt Page Blocks](https://github.com/Kntnt/kntnt-page-blocks) by using the WordPress plugins [Advanced Custom Fields (ACF) Pro](https://www.advancedcustomfields.com/pro/) and [Custom Content Shortcode (CCS)](https://wordpress.org/plugins/custom-content-shortcode/).

Thus, you need to install ACF Pro and CCS in WordPress. You also need a theme that allows content to go from edge to edge of the viewport. Optional you can use a theme builder such as [Beaver Themer](https://www.wpbeaverbuilder.com/beaver-themer/), [Oxygen Builder](https://oxygenbuilder.com/) or [Bricks Builder](https://bricksbuilder.io/).

You also need to download [kntnt-page-blocks.css](https://github.com/Kntnt/kntnt-page-blocks/blob/main/kntnt-page-blocks.css) from the Kntnt Page Blocks repository.

## Basic usage

If you only need a few pages with the brick capability, this approach is good enough.

1. Add [kntnt-page-blocks.css](https://github.com/Kntnt/kntnt-page-blocks/blob/main/kntnt-page-blocks.css) to your site. You can do that with a plugin like [Kntnt Style Editor](https://github.com/Kntnt/kntnt-style-editor) or [Simple Custom CSS and JS](https://wordpress.org/plugins/custom-css-js/), with WordPress’ Customizer or by adding it to your theme (which should be a child theme).
2. Install ACF and CCS.
3. Import acf.json into ACF.
4. Edit the location rules of the ACF field group *Page blocks* to your liking. (By default, it’s applied to all pages.)
5. Create a new page that matches the rule you set up.
6. Add the content of custom-content-shortcode.txt as body text.
7. Add as many bricks as you want.
8. Save. View. And be enchanted.

## Advanced usage

If you are using a theme builder, you should consider creating a template for all pages that match the rule you set up in step 4 above. Add the content of custom-content-shortcode.txt to that template. Now, you don’t have to do step 6 above.

## Confusing name

The project was named Kntnt Blocks from the beginning. But that was wrong choice given the meaning of “blocks” in WordPress. It’s therefore renamed to Kntnt Bricks. However, all code still uses the word “block” instead of “brick”. That’s unfortunate, but how it is for the time being.

## Frequently Asked Questions

### How do I know if there is a new version?

You can ["watch" the repository](https://docs.github.com/en/github/managing-subscriptions-and-notifications-on-github/about-notifications#notifications-and-subscriptions).

### How can I get help?

If you have questions about the code and cannot find an answer here, start by looking at [issues](https://github.com/kntnt/kntnt-page-blocks/issues) and [pull requests](https://github.com/kntnt/kntnt-page-blocks/pulls). If you still cannot find the answer, feel free to ask in the [issue tracker](https://github.com/kntnt/kntnt-page-blocks/issues) at Github.

### How can I report a bug?

If you have found a potential bug, please report it on the plugin’s [issue tracker](https://github.com/kntnt/kntnt-page-blocks/issues) at Github.

### How can I contribute?

Contributions to the code or documentation are much appreciated.

If you are unfamiliar with Git, please date it as a new issue on the plugin’s [issue tracker](https://github.com/kntnt/kntnt-page-blocks/issues) at Github.

If you are familiar with Git, please make a pull request.

## Changelog

### 1.0.0

The initial release.

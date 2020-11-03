
# TwentyTwenty Atomic Sass

## Description

A Sass adaptation of WordPress default theme for 2020 decomposed following atomic design principles (see https://bradfrost.com/blog/post/atomic-web-design/), to ease re-usability of this theme as a boilerplate for any new theme development.

---

**Theme Name:** Twenty Twenty  
**Theme URI:** https://wordpress.org/themes/twentytwenty/  
**Contributors:** the WordPress team  
**Requires at least:** WordPress 4.7  
**Version:** 1.1  
**License:** GPLv2 or later  
**License URI:** http://www.gnu.org/licenses/gpl-2.0.html  
**Tags:** blog, one-column, custom-background, custom-colors, custom-logo, custom-menu, editor-style, featured-images, footer-widgets, full-width-template, rtl-language-support, sticky-post, theme-options, threaded-comments, translation-ready, block-styles, wide-blocks, accessibility-ready

## Description

Our default theme for 2020 is designed to take full advantage of the flexibility of the block editor. Organizations and businesses have the ability to create dynamic landing pages with endless layouts using the group and column blocks. The centered content column and fine-tuned typography also makes it perfect for traditional blogs. Complete editor styles give you a good idea of what your content will look like, even before you publish. You can give your site a personal touch by changing the background colors and the accent color in the Customizer. The colors of all elements on your site are automatically calculated based on the colors you pick, ensuring a high, accessible color contrast for your visitors.

## Installation

1. In your admin panel, go to Appearance -> Themes and click the 'Add New' button.
2. Type in Twenty Twenty in the search form and press the 'Enter' key on your keyboard.
3. Click on the 'Activate' button to use your new theme right away.
4. Go to https://wordpress.org/support/article/twenty-twenty/ for a guide on how to customize this theme.
5. Navigate to Appearance > Customize in your admin panel and customize to taste.

## Copyright

Twenty Twenty WordPress Theme, Copyright 2019 WordPress.org. Twenty Twenty is distributed under the terms of the GNU GPL.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

Twenty Twenty is derived from the Chaplin Theme, Copyright 2019 Anders Norén. Chaplin Theme is distributed under the terms of the GNU GPL version 2.0.

Twenty Twenty bundles the following third-party resources:

Illustrations in screenshot.png by Tammie Lister
License: Creative Commons Zero (CC0), https://creativecommons.org/publicdomain/zero/1.0/  

Inter Font  
Copyright (c) 2016-2019 The Inter Project Authors (me@rsms.me)  
License: SIL Open Font License, 1.1, https://opensource.org/licenses/OFL-1.1  
Source: https://rsms.me/inter/  

Bespoke Icons Created For Twenty Twenty  
License: Creative Commons Zero (CC0), https://creativecommons.org/publicdomain/zero/1.0/  
List of bespoke icons:  
- Search icon  
- Menu icon  

Feather Icons  
Copyright (c) 2013-2017 Cole Bemis  
License: MIT License, https://opensource.org/licenses/MIT  
Source: https://feathericons.com  
Used for post meta icons, and the link icon in the social menu.  

Social Icons
License: GNU General Public License v2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Source: WordPress Social Link Block (See wp-includes\blocks\social-link.php)

Code from Twenty Nineteen  
Copyright (c) 2018-2019 WordPress.org  
License: GPLv2  
Source: https://wordpress.org/themes/twentynineteen/  
Included as part of the following classes and functions:  
- TwentyTwenty_SVG_Icons  
- twentytwenty_the_theme_svg()  
- twentytwenty_get_theme_svg()  
- twentytwenty_nav_menu_social_icons()  

Code from Twenty Seventeen  
Copyright (c) 2016-2019 WordPress.org  
License: GPLv2  
Source: https://wordpress.org/themes/twentyseventeen/  
Included as part of the following classes and functions:  
- twentytwenty_unique_id()  

Underscores  
https://underscores.me/, (C) 2012-2019 Automattic, Inc., [GPLv2 or later](https://www.gnu.org/licenses/gpl-2.0.html)  

## Changelog  

### 1.1  

* Released: December 12

- Add customizer option to show or hide author bio (#48550)
- Replace JS-based smooth scroll with CSS (#48551, #48763, #48866)
- Fix on mobile devices using a webkit browser, the menu and search modals could not be opened due to a TypeError: document.body is null (#48601)
- Fix correctly align the author bio and bottom post meta on single posts on mobile (#48619)
- Remove duplicate array key/value in TwentyTwenty_Non_Latin_Languages::get_non_latin_css() (#48624)
- Make the checkbox in the comment form larger and more consistent with other checkboxes (#48652)
- Fix typos in a variable name and inline comment in assets/js/color-calculations.js. (#48704)
- Fix placeholder misalignment in Firefox when a height is added as an inline style to the input field (#48876)
- Pass $post_meta and $location values to twentytwenty_start_of_post_meta_list and twentytwenty_end_of_post_meta_list actions to provide better context (#48906)
- Remove redundant echo for bloginfo() call in footer.php (#48918) 

### 1.0  

* Released: November 12, 2019  

Initial release  

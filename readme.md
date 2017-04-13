Houston Heat - Wordpress
==================================
Theme is modified from the twentysixteen wordpress theme. Sidebars are only used on the homepage to show practice signups and upcoming race events. All other pages follow a single column layout.

Pre-requisites
-----------------

Non-modified plugins
1.  Contact Form 7 (version ^4.7)
    * For Contact Us page
2.  Display Posts Shortcode (version ^2.7.0)
    * For customized static page to display current blog posts
3. Envira Gallery Lite (version ^1.6.0)
    * Used on Multimedia page
4. Simple Social Icons (version ^2.0.1)
    * Used in the social media super header / had to be hardcoded into  due to design requirements


Modified plugins
1. Wired Impact Volunteer Mangagement (version 1.3)
    * Used for event signup management and populates a widget on the homepage
    * https://github.com/BouncingPixel/wired-impact-volunteer-management
2. Very Simple Event List (version ^6.1)
    * Used to manage upcoming events. Widget is displayed on the top of the home page.
    * https://github.com/BouncingPixel/very-simple-event-list




Files changed
-------------------------
```
wp-content/
    plugins/
        wired-impact-volunteer-management/
        includes/
            class-opportunity.php
        templates/
            opp-single-form.php
            opp-single-meta.php
            opps-list-one-time.php
            opps-list-widget.php
    themes/
        twentysixteen/
        css/
            custom.css
        template-parts/
            page.php
        single.php
        footer.php
        functions.php
        header.php
        index.php
```
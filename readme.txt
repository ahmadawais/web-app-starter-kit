=== WordPress for Web Apps ===
Contributors: cferdinandi
Tags: membership, app, login, front-end
Requires at least: 3.0.1
Tested up to: 3.6.1
License: MIT
License URI: http://gomakethings.com/mit/

Transform WordPress into a web app engine.

== Description ==

WordPress for Web Apps provides the essential components you need to power your web app with WordPress:

* Front-end login, sign-up, password reset, and password change forms.
* Separate navigation menus for logged-in and logged-out users.
* User access settings, so you can selectively hide content from logged-out (or logged-in) users.
* Security settings let you set password requirements, hide the admin bar, and block backend access.
* The web app settings panel lets you easily configure error messages, button text, and more.

== Installation ==

1. Upload the `wordpress-for-web-apps` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Visit GitHub for [tutorials and support](http://cferdinandi.github.io/web-app-starter-kit/).

== Frequently Asked Questions ==

Please visit GitHub for [tutorials and support](http://cferdinandi.github.io/web-app-starter-kit/).

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the /assets directory or the directory that contains the stable readme.txt (tags or trunk). Screenshots in the /assets
directory take precedence. For example, `/assets/screenshot-1.png` would win over `/tags/4.3/screenshot-1.png`
(or jpg, jpeg, gif).
2. This is the second screen shot

== Changelog ==

= v3.0 (September 28, 2013) =
* Converted from a collection of theme functions to a plugin.
* Completely rebuilt forms for better consistency, security, and UX.
* Changed signup process: user creates their own password and can login immediately.
* Changed password reset process: user selects their new password (not WordPress).
* Added password requirement check to signup and password change and reset processes.
* Integration with `wp_nav_menu()` for separate logged-in and logged-out navigation with any theme.
* Added Web App Settings page for easier adjustment of alerts, security settings, form styling, and more.

= v2.1 (June 7, 2013) =
* Switched to MIT license.

= v2.1 (June 6, 2013) =
* Split functions into individual files for easier inclusion and exclusion.

= v2.0 (May 17, 2013) =
* Completely rebuilt.

= v1.0 (January 23, 2013) =
* Initial release.

== Roadmap ==

= Version 3.x =
* Custom "password reset" and "welcome message" email settings.
* Add "Delete Account" option to the front-end for users.
* Add "Update Profile" options to the front-end for users.

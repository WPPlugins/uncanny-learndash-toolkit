=== Uncanny LearnDash Toolkit ===
Contributors: uncannyowl
Tags: LearnDash, eLearning, LMS
Requires at least: 4.0
Tested up to: 4.8
Stable tag: 2.0.6
License: This plugin is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 2 of the License, or any later version.   LearnDash Groups in User Profiles is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.   You should have received a copy of the GNU General Public License along with LearnDash Groups in User Profiles. If not, see {URI to Plugin License}.
License URI: https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html

Extend LearnDash with a variety of useful functions that make it even easier to build great learner experiences with LearnDash.

== Description ==
**Important: This plugin requires PHP 5.3 or higher and LearnDash 2.1 or higher.**

The Uncanny LearnDash Toolkit adds a dozen exciting new features to LearnDash sites that improve the learner experience and make development easier. 

https://www.youtube.com/watch?v=FKsN0oTx-rM

The Uncanny LearnDash Toolkit adds the following features to your LearnDash site:

* **Front End Login**: Replace wp-login with a simple shortcode that you can drop onto any page to allow better branding of the login experience. User verification is also available to manage registrations.
* **Hide Admin Bar**: Hide the WordPress admin bar for any roles that you want.
* **LearnDash Resume Button**: Allow users to pick up where they left off in a LearnDash course by clicking a button.
* **LearnDash Groups in User Profiles**: Easily identify LearnDash Group membership from user profile pages.
* **Login Redirect**: Send learners to a custom dashboard or course after they sign in.
* **Menu Item Visibility**: Control the visibility of menu entries based on whether or not the user is signed in.
* **Show LearnDash Certificates**: Use a simple shortcode to display a list of all certificates (course and quiz) earned by the current user.
* **Show or Hide Content**: Use shortcodes to show or hide content based on whether or not a user is signed in. Great for Open course types.
* **Log In/Log Out Links**: Add Log In and Log Out links to menus, or to any page or widget with a shortcode.
* **LearnDash Breadcrumbs**: Add breadcrumb links that support courses, lessons, topics and quizzes. Also supports woocommerce, custom post types with or without taxonomies & tags, pages and blog posts.

More information about how to use the Toolkit, including a 40-minute instructional screencast, is available at (http://www.uncannyowl.com/uncanny-learndash-toolkit/).

We welcome contributions to the Uncanny LearnDash Toolkit! The plugin is managed in a [Bitbucket Repository](https://bitbucket.org/uncannyowl/uncanny-learndash-toolkit). 

== Installation ==
1. Upload the contents of the plugin zip file to the `/wp-content/plugins/` directory.
2. Activate the plugin through the Plugins menu in WordPress.

== Screenshots ==
1. Uncanny LearnDash Toolkit Dashboard

== Changelog ==

= 2.0.6 =
* Fixed: Single quotes are saved properly in toolkit module settings
* Fixed: Front end login reset password function on Edge and Safari

= 2.0.5 =
* Fixed: WooCommerce/Third Party plugin notices popping up in Pro Toolkit Ad banner
* Fixed: Modules not loading because DB updates were not saving slashes on some hosts
* Fixed: Password reset when WordPress is installed in a subdirectory

= 2.0.4 =
* Fixed: Restored 'Sample Tag' module
* Fixed: Removed invalid slashes when saving settings

= 2.0.1 =
* Fixed: Flush admin scripts/styles

= 2.0 =
* Added: Module filtering options in the Toolkit UI
* Fixed: Minor issue in auto-completion logic when multiple quizzes are assigned to the topic/lesson
* Fixed: Front End Login now accepts username or email if user approval is turned on
* Fixed: Minor layout issue in WordPress menu editor when Menu Item Visibility module is enabled

= 1.3.5 =
* Added: Textarea as an option for module settings
* Added: Priority 11 to menu item visibility filter; will now override common theme menu enhancements like megamenu

= 1.3.4 =
* Removed: Dynamic announcement banner to admin UI

= 1.3.3 =
* Added: Dynamic announcement banner to admin UI
* Updated: Changed log in link shortcode [uo_login] to [uo_login_link]
* Fixed: Log in link redirects to login empty

= 1.3.2 =
* Added uo_login_link shortcode to replace deprecated uo_login in Login/Logout Menu
* Added WordPress 4.6 support
* Improved design of module settings
* Improved compatibility with Nav Menu Roles plugin
* Fixed LearnDash Group User Profile module to only show group name if group ID is valid
* Fixed multiple escape slash issue with custom module
* Fixed auto completion of lessons if topics are complete but quiz is not
* Reworded Front-End Login error label

= 1.3.1 =
* Blocked Pro reminders from appearing on page reloads after dismissal

= 1.3.0 =
* Added logout redirect setting
* Added color pickers
* Added links to Pro modules plugin
* Added admin notification when user is manually approved
* Added links to Knowledge Base articles for all modules
* Fixed automatic approval of assignment when Topics Autocomplete Lessons module is on
* Fixed widget certificate link
* Enhanced security for mark lessons complete

= 1.2.7 =
* Fixed learndash_lesson_completed to allow hooks from BadgeOS and other plugins
* Fixed Topics Auto Complete Lessons invalid argument for foreach() for non-logged in users
* Fixed fix notice on 404 pages
* Fixed do not setup resume button if last page has been deleted
* Excluded admin users from manual verification script

= 1.2.6 =
* Allowed certificates with the same name
* Fixed Uncanny Certificate Widget closing </div> tag

= 1.2.5 =
* Fixed course completion date issue with Topics Autocomplete Lessons
* Added support for alternate course labels (Thanks Eben Hale!)

= 1.2.4 =
* Added PHP/LearnDash/WP version checking
* Fixed cookies for password reset and registration
* Updated resume button to match theme button style
* Fixed verified user email formatting

= 1.2.3 =
* Tested with WordPress 4.5
* Fixed breadcrumbs function

= 1.2.2 =
* Fixed duplicate breadcrumbs on quiz pages

= 1.2.1 =
* Fixed missing file

= 1.2 =
* NEW FEATURE: LearnDash Breadcrumbs
* Fixed course completion time in CSV output
* Fixed translation text domain
* Added sorting of features by name on admin settings page
* Added bitbucket pull requests for developers
* Fixed all shortcode now use _ rather than -
* Dev Only Added simple user registration to Front End Login feature
* Added translation support
* Fixed course completion time in LearnDash CVS Reports

= 1.1 =
* NEW FEATURE: Log In/Log Out Links
* Fixed redirect from wp registration page
* Added registration link to uo_login_ui
* Added setting to change Resume button text

= 1.0.1 =
* Open Certificate links in new window
* Fixed blank settings page on older server configuration
* Fixed auto loading on older server configuration
* Fixed settings modal on small screens
* OB Clean Buffer Before AJAX Response
* Improved support for custom extensions
* Set Addon Option default as Array()
* Prevented login lockout if login page set incorrectly

= 1.0 =
* Public release

== Upgrade Notice ==

None
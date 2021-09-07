=== Benutzernamen Verfügbarkeitsprüfung ===
Contributors: DerN3rd
Tags: buddypress, buddypress registration, username, registration, new user
Requires at least: 4.0
Tested up to: 5.2.4
Stable tag: 1.1.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WordPress Username availability checker checks if a username is available or not.

== Description ==
WordPress-Benutzernamen-Verfügbarkeitsprüfung für WordPress & BuddyPress prüft die Verfügbarkeit von Benutzernamen auf den Registrierungsbildschirmen für neue Benutzer.
Es unterstützt Benutzer und Webseiten-Administratoren, indem es sie mit Ajax benachrichtigt, ob der von ihnen eingegebene Benutzername verfügbar ist oder nicht.

= Features =

*	Überprüft die Verfügbarkeit von Benutzernamen im WordPress-Admin-Bildschirm „Neuer Benutzer“
*	Überprüft die Verfügbarkeit von Benutzernamen auf der WordPress-Standardregistrierungsseite
*	Prüft die Verfügbarkeit auf der BuddyPress-Registrierungsseite

Für Screenshots und weitere Details besuche bitte [Benutzernamen Verfügbarkeitsprüfung Seite](https://n3rds.work/docs/benutzernamen-verfuegbarkeitspruefung-handbuch/ "Plugin page" )



== Installation ==

1. Download `username-availability-checker-x.y.z.zip` , x.y.z are version numbers eg. 1.0.0
1. Extract the zip file
1. Upload `username-availability-checker` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

You can also visit Dashboard->Plugin->Add New and search for "psource User Name Availability Checker" and install from there.

== Frequently Asked Questions ==

= How do I get support? =

Please use psource forums for any support question. We are helpful people and stand behind our plugins firmly.


== Screenshots ==

See [Username Availability Checker plugin page](https://n3rds.work/docs/benutzernamen-verfuegbarkeitspruefung-handbuch/ "Plugin page" ) for screenshots.

== Changelog ==
= 1.1.6 =
 * If BuddyPress is active, remove space between the words before checking for availability.

= 1.1.6 =
 * Sanitize username before checking. Helps solve the space and dashes issue.

= 1.1.5 =
 * Fix the undefined function 'get_current_screen'. Thank you Loïc for reporting.

= 1.1.4 =
 * Improve error messages show to the user on invalid username.

= 1.1.3 =
 * Tested with WordPress 5.2.1/BuddyPress 4.3

= 1.1.2 =
 * Add compatibility with WordPress Ajax Login Plugin
 * Rename plugin to WordPress User Name availability Checker.

 = 1.1.1 =
 * Allow using filter to add extra username selectors
= 1.1.0 =
 * Initial release on wp.org repo
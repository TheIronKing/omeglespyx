## Version: 3.3.1 ##
  * Changed a few hotkeys for an upcoming new feature
  * Added an option to share conversations online by generating a link to a PasteHTML page
  * Added a new status panel to replace some announcements
  * Fixed the bug causing the program to search for multiple conversations when the New Convo button was used with Auto Reconnect

## Version: 3.3 ##
  * Temporarily removed the boldening of filtered words because it was causing too many issues
  * Added support for other languages (most languages that Omegle supports)
    * Note: This will not affect the program itself (yet), but only the language that the strangers are speaking
  * Fixed a bug where the word filter was sometimes changing the case of filters
  * Improved a few bugs where the program would freeze and have to be reloaded (added the 'Cancelling search...' announcement).
  * Added Export and Import features to the Word Filter
  * The Word Filter can no longer hold duplicate values

## Version: 3.2.6 ##
  * Fixed a bug with sounds sometimes not being played on OS other than Windows 7
  * Actually fixed the HTML-tag bug this time (yay!)

## Version: 3.2.5 ##
  * Error message for the connection taking too long disabled when using common interests
  * HTML tags being shown for strangers issue fixed
    * Note: sending messages that contain HTML will be visible to you, but the HTML is removed for strangers

## Version: 3.2.4 ##
  * A few small updates with the start-up message
  * A few other small UI updates

## Version: 3.2.3 ##
  * Updated the DeathByCaptcha library
  * Added ChatterBot library for future Cleverbot development
  * Added an error message to 'Finding two strangers...' "bug"
  * Error messages are now displayed in red
  * Words filtered by the Word Filter are now highlighted in bold
  * The Word Filter no longer recognizes numbers as separators (something like '17m' will now be filtered)
  * The Word Filter no longer re-filters words that have already been filtered
    * For example: if you filter m -> f, and f -> m, instances of 'm' that have been filtered to 'f' will be ignored when filtering f -> m
  * Preferences for the word filter sorting are now saved
  * Both the sorting and case sensitivity added to the reset function
  * Added a little start-up message

## Version: 3.2.2 ##
  * Separated the connection and update check
  * Fixed a bug where one stranger was sometimes staying connected throughout convos
  * The word filter no longer recognizes the apostrophe as a separator (for contractions like "I'm", etc.)
  * Added a sorting option to the Word Filter
  * Added a case sensitivity option to the Word Filter

## Version: 3.2.1 ##
  * Removed multi-threading on finding new strangers - the bot was connecting to itself more often than I anticipated
  * Fixed a small connection bug and added an error message for it
  * Changed the word filter to more intelligently filter characters and word sets

## Version: 3.2 ##
  * Fixed the program putting you into Omegle's naughty corner
  * Fixed the bug where sometimes strangers randomly disconnected
  * Added a few options to the Word Filter and redesigned the window
  * Added a 'Reset Application' option in the help menu
  * Added a disconnection sound
  * Strangers are now searched for simultaneously - this means much faster connection times (and occasionally that Stranger 2 connects before Stranger 1

## Version: 3.1.3 ##
  * Fixed the multiple issues with the word filter
  * Fixed the issues with common interests
  * Fixed the issue where the reload function wasn't saving preferences

## Version: 3.1.2 ##
  * Removed the pesky config file - the program now makes use of the Preferences class
  * Program brought back on to JDK 1.7 (you will now need JRE 7 to run it)

## Version: 3.1.1 ##
  * Fixed the reload button (now works on all OS)

## Version: 3.1 ##
  * Common interests feature brought back due to popular demand (you demanding motherfuckers! :P)
  * Check box added to Word Filter

## Version: 3.0.2 ##
  * Added Reload button

## Version: 3.0.1 ##
  * Fixed the config file

## Version: 3.0 ##
  * Captcha bug fixed
  * Common interests feature removed
  * Complete re-design of the menu
  * Added a toolbar (finally)
  * Some icons improved/added
  * Word Filter' function added
  * A number of new buttons added to the new 'Help' menu
  * The program now properly stores messages sent while only one stranger is connected
  * Message sounds added
  * Some accelerators added/changed
  * Splash screen gfx improved
  * A few 'fun' features added - try sending 'trololol' or '(asterisk)facepalm(asterisk)' as a message
  * Various other small changes to window icons, etc.

## Version: 2.3.1b ##
  * The block messages function now preserves its state through conversations
  * New splash screen implemented

## Version: 2.3.1 ##
  * Messages that are sent before both strangers are connected are saved and resent when both strangers connect to the chat
  * The homepage button now works on all operating systems
  * An update check is now performed when the program starts
  * Some small UI updates

## Version: 2.3 ##
  * Added a few fixes to the captcha system
  * Added a complaint window for captchas (allows you to complain to Omegle)
  * Added support for Omegle's 'common interests' feature (still in beta)
  * Added many new servers to the server list
  * A few other small UI glitches and bug fixes dealt with

## Version: 2.2.1 ##
  * Added a captcha settings window
  * Added support for DeathByCaptcha
  * Fixed the "An error has occurred" error.
  * Changed program logo

## Version: 2.2.1 BETA ##
  * Added support for DeathByCaptcha (still needs heavy testing)
  * Starting building Troll Mode (next release probably)
  * Fixed the "An error has occurred :(" error.

## Version: 2.2 ##
  * Some small UI changes
  * Block Message feature tweaked slightly
  * Initialization process improved
  * A few small improvements to the captcha system
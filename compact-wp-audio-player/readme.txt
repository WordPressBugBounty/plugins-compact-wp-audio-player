=== Compact WP Audio Player ===
Contributors: Tips and Tricks HQ, mbrsolution
Donate link: https://www.tipsandtricks-hq.com/development-center
Tags: audio, audio player, embed, media, media player, mp3, mp3 player, music, music player, podcast
Requires at least: 5.0
Tested up to: 6.7
Stable tag: 1.9.15
License: GPLv2 or later

A Compact WP Audio Player Plugin that is compatible with all major browsers and devices (Android, iPhone, iPad)

== Description ==

Compact WordPress Audio Player plugin is an HTML5 + Flash hybrid based wordpress plugin which can be used to embed an mp3 audio file on your WordPress post or page using a shortcode. The audio player is cute and compact and will play on all major browsers. 

This audio player plugin Supports .mp3 and .ogg file formats.

The audio files that you embed using this plugin will work on all devices.

= Features =
* The audio player is compact so it does not take a lot of real estate on your webpage
* HTML5 compatible so the audio files embedded with this plugin will play on iOS devices
* Works on all major browsers - IE7, IE8, IE9, Safari, Firefox, Chrome
* The audio player is responsive.
* If you do podcasting then this audio player can be used to embed the audio files on your WordPress posts or pages
* If you are selling audio files from your site then you can use this plugin to offer a preview
* Add the audio player to any post/page using shortcode
* Use autoplay option to play an audio/mp3 file as soon as the page loads
* Ability to specify both the mp3 and ogg version of your audio files. The plugin will play the appropriate one based on the device. 

https://www.youtube.com/watch?v=4eBIPqfZiss

More details can be found on the [Compact Audio Player Plugin Page](https://www.tipsandtricks-hq.com/wordpress-audio-music-player-plugin-4556)

== Installation ==

1. Upload the "sc_audio_player.zip" file via the WordPress's plugin uploader (Plugins -> Add New -> Upload)
2. Activate the plugin through the "Plugins" menu in Wordpress.
3. Create a page or post to show the player using shortcode. 
4. Add shortcode anywhere in the post/page like: [sc_embed_player fileurl="mp3 file url"]

== Usage ==
Use the following shortcode to embed an audio file anywhere on your site

[sc_embed_player fileurl="URL OF THE MP3 FILE"]

Example shortcode:

[sc_embed_player fileurl="http://www.example.com/wp-content/uploads/my-music/mysong.mp3"]

== Screenshots ==
Visit the following page for screenshots
https://www.tipsandtricks-hq.com/wordpress-audio-music-player-plugin-4556

== Frequently Asked Questions ==

= Will my audio file work in all major browsers? =
Yes

= Can I loop the audio files embedded using this plugin? =
Yes

= Will the audio player work on iOS devices?
Yes

== Upgrade Notice ==
None

== Changelog ==

= 1.9.15 =
- Using the `wp_safe_remote_get` function instead of `wp_remote_get` to get the file headers.

= 1.9.14 =
- Added output escaping to the fileurl shortcode parameter.
- Refactored the autoplay JavaScript code so output escaping can be added easily.

= 1.9.13 =
- Added a settings option and a filter to disable the URL validation for the fileurl parameter.

= 1.9.12 =
- The fileurl field will also accept the relative URL value (example: /wp-content/uploades/audio.mp3)

= 1.9.11 =
- Added a fallback for the fileurl verification when the PHP URL validation fail for non-latin characters.

= 1.9.10 =
- Added a CSS wrapper class for the audio player to make it work better with block themes.
- Validate URL for the 'fileurl' parameter of the shortcode.

= 1.9.9 =
- PHP 8.2 compatibility.

= 1.9.8 =
- Added output escaping to the shortcode parameters. Thanks to WPScan for pointing it out.

= 1.9.7 =
- Escape attributes in the shortcode.
- Added nonce check to the settings menu save operation.
- Thanks to WPScan team for pointing these out.
- WP 5.8 compatibility.

= 1.9.6 =
- Updated the audio player for iOS 10 safari.
- WordPress 4.6 compatible.

= 1.9.5 =
- Bugfix - Audio player embedded with the "autoplay" flag (in the default template) wasn't changing the pause button icon to a play button icon after the audio file finished playing.

= 1.9.4 =
- WordPress 4.4 compatibility.

= 1.9.3 =
- Corrected a typo in the play button image file name.
- changed the uniqid() function to use the "more_entropy" parameter so the value is more unique.
- Fixed a minor bug with internet explorer.

= 1.9.2 =
- Fixed a minor bug (new player template1) with the "loops" parameter.

= 1.9.1 =
- Fixed a minor bug in the new player template1 with the "autoplay" parameter.

1.9 - Added a new shortcode for a different audio player with seek bar and volume control in the player. The documentation has usage details of this new shortcode.

1.8 - Added the option to specify both an .mp3 and .ogg version of the audio file in the shortocode.

1.7 - WordPress 3.8 compatibility

1.6 - Added an option to disable simultaneous playback. It will automatically stop the audio file that is currently playing when a user plays a new file. 

1.5 - added a auto loop parameter option in the shortcode to automatically loop the audio file

1.4 - added a volume parameter option in the shortcode so you can specify the volume of the audio

1.3 - Added the autoplay option in the shortcode.

1.2 - added the ability to spcify a container class via the shortcode (helpful for CSS customization)

1.1 - minor javascript bug fix

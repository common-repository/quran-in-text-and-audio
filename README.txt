=== Quran in Text and Audio ===
Contributors: maidulcu
Donate link: https://dynamicweblab.com
Tags: Quran, Surah, ayah, full quran
Requires at least: 3.0.1
Tested up to: 6.5.2
Requires PHP: 7.0
Stable tag: 1.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Show Full Quran or single verses with audio.

== Description ==

[Quran Demo](https://dynamicweblab.com/demo/plugins/quran/)

The Quran is the holy book of Islam, and for many Muslims, hearing the verses of the Quran recited is a powerful spiritual experience.

Quran in Text and Audio plugin allows you to embed any verse of the Qu’ran.
The surah, editions, and verses data are all available under the public API of https://alquran.cloud/api.
Terms and Conditions https://alquran.cloud/terms-and-conditions

Features:

*   Show full Quran with translation.
*   Show a single Surah.
*   Show a random Surah.
*   Show a single ayah.
*   Show a random ayah.

Show Via Shortcode:

Show Full Quran:

<code>[quran_full]</code>

Show single Surah:

<code>[quran_surah surah=1]</code>

Show Random Surah:

<code>[quran_surah random=true]</code>

Show single ayah:

<code>[quran_ayah ayah=1]</code>
The Quran contains 6236 verses.

Show Random ayah:

<code>[quran_ayah random=true]</code>

== Installation ==

INSTALL WITHIN WORDPRESS


1. Visit the plugins page within your dashboard and select ‘Add New’
2. Search for "Quran in Text and Audio"
3. Activate "Quran in Text and Audio" from your Plugins page


INSTALL MANUALLY

1. Upload `quran-in-text-audio` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Screenshots ==

1. Full Quran with audio
2. Single surah
3. Single ayah

== Changelog ==

= 1.0.0 =
* Initial Release

= 1.0.1 =
* Update text domain
* Conditionally load css
* Small css color fix
* Replace native php function with wordpress one
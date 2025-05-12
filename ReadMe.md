<p align="center"><img src="docs/icon.png"></p>
<h1 align="center">YouTube-Comment-Translate (Added Firefox support)</h1>

This is a Firefox port of toluschr/YouTube-Comment-Translate.

* [Usage](#usage)
    * [Changing the language](#changing-the-language)
* [Manual Install](#manual-install)
    * [Javascript injector](#javascript-injector)
    * [Chromium](#chromium)
    * [Other](#other)

## Usage

Reload any open YouTube page after installation. A translate button will then appear in the header of every comment. </br>

<img src="docs/usage.gif">

### Changing the language

By default, the extension translates to english (en). If the extension was

When using a JavaScript injector as the installation method, manually edit
`inject.js` and change line 5 (`TARGET_LANGUAGE`) to the desired language.

A list of supported languages can be found here: <https://www.gnu.org/software/gettext/manual/html_node/Usual-Language-Codes.html>

## Manual Install

### Javascript injector

Since this plugin uses a content-script, it should work on any browser that
supports a [Javascript injector](https://github.com/Lor-Saba/Code-Injector).

This is also the recommended method for firefox users. Use the following url
pattern: `www\.youtube\.com`

<img src="docs/injector.png">

The icons used in the README are from the open-source [papirus-icon-theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) project

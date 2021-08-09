# MaterialFox
*A Material Design-inspired userChrome.css theme for Firefox*

![Preview](https://user-images.githubusercontent.com/5405629/45172944-21d91900-b24a-11e8-8bc5-03814121b0de.png)
This theme is powered by blood, sweat, and coffee. If you like it, please consider helping out to support its continued development.

[![Buy me a coffee](https://svgshare.com/i/8Yd.svg)](https://www.buymeacoffee.com/n4ho5QX2l)

## What this does
Inspired by Google's Material Design and their latest Google Chrome UI, this theme turns your Firefox into a Material-styled web browser. The aim was to style the browser as closely as possible to Google Chrome, where practical.

This is a userChrome.css theme, which means you must manually add it to your Firefox profile. The theme overrides certain browser styles. Currently, only the main UI is affected (settings pages, etc. are not). More elements of the UI may be styled in the future but a broader scope becomes harder to maintain as Mozilla updates their browser code so some UI styles may be culled or redone if they become unmaintainable.

## What version do I use?
Check the [releases](https://github.com/muckSponge/MaterialFox/releases) section. Each release version will match the compatible Firefox version. For example, if you're using Firefox 88, try a v88.x release. If there's no matching release and you're not using an old version of Firefox, go for the latest one. If you're using a beta version of Firefox, you might want to try the master branch, which will have the latest bug fixes.

## Installation
1. Copy the chrome folder and user.js file into your Firefox profile directory. To find your profile directory, go to about:support or about:profiles.
2. See [Recommended instructions](#recommended-instructions) if you'd prefer a more Chrome-like experience.
3. Restart Firefox.

### Recommended instructions
Add space above tab bar:
* Right click on toolbar -> Customize.
* Check Drag Space checkbox.

Replicate Chrome behaviour for clipped tabs:
* [about:config] Set ```browser.tabs.tabClipWidth``` to ```83``` (default is ```140```).

Replicate Chrome's "Not Secure" text on HTTP:
* [about:config] Set ```security.insecure_connection_text.enabled``` to ```true```.

## Please note
* Linux is no longer officially supported but you can give it a try – if you'd like to work on it feel free to make a PR.
* Some customisation settings may no longer work (such as compact/touch density).
* Some custom themes may clash with the address bar.
* Some themes using transparency might not work.

# MaterialFox
*A Material Design-inspired userChrome.css theme for Firefox*

![Preview](https://user-images.githubusercontent.com/5405629/44436935-13a8bd00-a5fb-11e8-8912-a0b54da95c45.png)

## What this does
Inspired by Google's Material Design and their latest Google Chrome UI, this theme turns your Firefox into a Material-styled web browser. The aim was to style the browser as closely as possible to Google Chrome, where practical. Google Chrome is by no means a perfect implementation of the Material Design philosophy and as such, the theme deviates from Google Chrome in some areas to provide a better experience.

This is a userChrome.css theme, which means you must manually add it to your Firefox profile. The theme overrides certain browser styles. Currently, only the browser-toolbox and titlebar are affected (essentially, the chrome at the top of the browser). Other elements of the UI may be styled later.

## Installation
1. Copy the chrome folder into your Firefox profile directory. To find your profile directory, go to about:support.
2. Go to about:config and search for ```svg.context-properties.content.enabled```; make sure it is set to ```true```.
3. For right-aligned new tab button (entirely optional):
    * Install [Simple New Tab Button](https://addons.mozilla.org/en-US/firefox/addon/simple-new-tab-button/) and drag the button to the far right of your tab bar.
    * Remove the built in new tab button.
4. Restart Firefox.

## Please note
Tested on macOS and Windows. Windows may have oversized titlebar buttons and/or they may overlap with UI in fullscreen. The private browsing mode indicator might obscure the right-aligned new tab button.

# MaterialFox-BigSur
  Forked from [MaterialFox](https://github.com/muckSponge/MaterialFox)
  
![Preview](https://user-images.githubusercontent.com/56245920/100540817-218e2380-3283-11eb-915f-e1cd2e319c0e.png)

## What is the difference?
* Big-Sur Style UI
  * Applies the translucency and blur effect on the tab bar
  * Removes the gray background from the URL & search bar
  * Gives every icon a little bit more space to breathe
* Cleaner Look
  * Makes the bookmarks bar (aka PersonalToolbar) appear only when you hover over the top of the window

## How do I install?
Follow [Installation](#installation).  
Please note that this will only work properly on macOS.

## Acknowledgements
* [MaterialFox](https://github.com/muckSponge/MaterialFox)
* [firefox-macos-native-tabbar](https://github.com/zvuc/firefox-macos-native-tabbar)
* [firefox-sliding-bookmarks-bar](https://github.com/zvuc/firefox-sliding-bookmarks-bar)
  
***
Below is the original README.md from MaterialFox.
***

*A Material Design-inspired userChrome.css theme for Firefox*

![Preview](https://user-images.githubusercontent.com/5405629/45172944-21d91900-b24a-11e8-8bc5-03814121b0de.png)
This theme is powered by blood, sweat, and coffee. If you like it, please consider helping out to support its continued development.

[![Buy me a coffee](https://svgshare.com/i/8Yd.svg)](https://www.buymeacoffee.com/n4ho5QX2l)

## What this does
Inspired by Google's Material Design and their latest Google Chrome UI, this theme turns your Firefox into a Material-styled web browser. The aim was to style the browser as closely as possible to the latest Google Chrome dev builds, where practical.

This is a userChrome.css theme, which means you must manually add it to your Firefox profile. The theme overrides certain browser styles. Currently, only the main UI is affected (settings pages, etc. are not). More elements of the UI may be styled in the future.

## What version do I use?
Check the [releases](https://github.com/muckSponge/MaterialFox/releases) section. Each release version will match the compatible Firefox version. For example, if you're using Firefox 76, try a v76.x release. The master branch is compatible with stable Firefox; the beta branch is compatible with Firefox Beta. This requires a periodic rebase of master on beta as Mozilla update their release cycle (which doesn't always occur immediately).

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
* Linux is not frequently tested; last tested on 21/05/2019.
* Some customisation settings may no longer work (such as compact/touch density).
* Some custom themes may clash with address bar.

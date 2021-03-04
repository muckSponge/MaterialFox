# MaterialFox-BigSur
  Forked from [MaterialFox](https://github.com/muckSponge/MaterialFox)
  
![Preview](https://i.imgur.com/qvgq4yP.png)

## What is the difference?
* macOS Big Sur Style UI
  * macOS style translucent blur effect is applied on the tab bar.
  * The gray background is removed from the URL & search bar.
  * Every icon is given a little bit more space to breathe.
* Cleaner Look
  * The bookmarks bar (aka PersonalToolbar) appears only when you hover over the top of the window. If you are not a fan of this, you can [disable it](#if-you-dont-like-the-auto-hiding-bookmark-bar).
  * The tab close button from inactive tabs are hidden. (You can hover over the tab to make it appear.)
  * Animations have been refined.

## How do I install?
Follow [Installation](#installation).  
Please note that you can install this on both Windows and macOS but it'll work as intended *only on macOS*.

## If you don't like the auto-hiding bookmark bar
After installation, open userChrome.css and *delete* the line 10, save the file, and then restart Firefox.  
```css
@import "bookmarkAutoHide.css";
```
You can also delete the file bookmarkAutoHide.css or keep it for later.

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

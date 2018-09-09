# MaterialFox
*A Material Design-inspired userChrome.css theme for Firefox*

![Preview](https://user-images.githubusercontent.com/5405629/45172944-21d91900-b24a-11e8-8bc5-03814121b0de.png)

## What this does
Inspired by Google's Material Design and their latest Google Chrome UI, this theme turns your Firefox into a Material-styled web browser. The aim was to style the browser as closely as possible to the latest Google Chrome dev builds, where practical.

This is a userChrome.css theme, which means you must manually add it to your Firefox profile. The theme overrides certain browser styles. Currently, only the UI at the top of the browser is affected. Other elements of the UI may be styled later.

## Installation
Some steps involve accessing the about:config page. You can get there by typing it into your urlbar.

### Mandatory steps
1. Copy the chrome folder into your Firefox profile directory. To find your profile directory, go to about:support. Alternatively, you can symlink your chrome folder instead of copying.
2. [about:config] Set ```svg.context-properties.content.enabled``` to ```true``` (default is ```false```).
3. Restart Firefox.

### Optional steps
Replicate Chrome's light color scheme:
* Right click on toolbar -> Customize.
* Click Themes.
* Select Light theme.

Add space above tab bar:
* Right click on toolbar -> Customize.
* Check Drag Space checkbox.

Replicate Chrome behaviour for clipped tabs:
* [about:config] Set ```browser.tabs.tabClipWidth``` to ```83``` (default is ```144```).

Replicate Chrome identity colours (or lack thereof):
* [about:config] Add new entry ```materialFox.disableIdentityColors``` with value ```true```.
* Restart Firefox.

Remove pocket button from Address Bar:
* Right click on pocket button -> Remove from Address Bar

## Please note
* Linux is not frequently tested; last tested on 07/09/2018.
* Some customisation settings may no longer work (compact density, some custom themes).
# Unified Dark

## Description
Unified Dark is a custom Firefox CSS theme which aims to simply the look of Firefox by moving the navigation bar, the tabs, extensions, and other buttons all on a single line as opposed to being stacked on top of one another.

## Installation

- In the ```about:config``` page on your Firefox browser, set the following parameters to **True** :
  - ```toolkit.legacyUserProfileCustomizations.stylesheets```
  - ```layers.acceleration.force-enabled```
  - ```gfx.webrender.all```
  - ```svg.context-properties.content.enabled```
- Copy the userChrome.css file from this repository to your **chrome** folder. You can find the **chrome** folder here :
  - On Linux : ```$HOME/.mozilla/firefox/######.default-release/chrome/```
  - On Windows : ```C:\Users\[USERNAME]\AppData\Roaming\Mozilla\Firefox\Profiles\######.default-release\chrome\```
  - On MacOS : ```Users/[USERNAME]/Library/Application Support/Firefox/Profiles/######.default-release/chrome```
  - If it doesn't exist already create a folder called chrome

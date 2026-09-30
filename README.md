# Firefox Newtab Fix

This is a simple fix for FireFox's latest NewTab changes. The shortcut icons are way too close together and the page content doesn't feel vertically centered enough. This Repository employs a simple CSS file to fix the issue.

Note: As of 2026-08-03, this Repository is becoming more of a general CSS fix for Firefox. See the full changes below.

## Change List

- Fix NewTab icon spacing
- Fix top Search Bar not allowing text highlighting
- Fix the Background Color being too dark

## Installation

1. Enable Custom Stylesheets
   1. Type `about:config` in your address bar and press `Enter`
   2. Click "Accept the Risk and Continue"
   3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
   4. Set the value to true
2. Locate Your Profile Folder
   1. Type `about:profiles` in your address bar and press `Enter`
   2. Find the currently in-use profile and open its folder (probably the root directory one)
   3. Copy the `chrome` folder from the repository into the opened profile folder
3. Restart FireFox

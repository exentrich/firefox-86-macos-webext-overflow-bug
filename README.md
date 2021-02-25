# Reproducable webextension
In Firefox 86 (only in macOS) for some reason such simple webextension have a bug.
Here what happening:
- `browser_action` popover have a div with `display: flex` with two child div's
- each of this div`s have a `overflow: auto`
- scroll works for first div, but doesn't for second

![alt text](https://github.com/exentrich/firefox-86-macos-webext-overflow-bug/raw/master/bug.png "bug")
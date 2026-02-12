# Republican to American Fascist Replacer (Firefox)

A Firefox extension that automatically replaces terms like "Republican", "GOP", and "ICE" with "American Fascist" and "Gestapo" on all websites you visit.

## Installation Instructions

Since this extension is not currently on the Firefox Add-ons Store, you must install it manually as a temporary add-on:

1. **Download the files**: 
   - Ensure you have both `manifest.json` and `content.js` in a folder on your computer.
2. **Open Firefox Debugging**:
   - In your Firefox address bar, type `about:debugging#/runtime/this-firefox` and press Enter.
3. **Load Temporary Add-on**:
   - Click the **Load Temporary Add-on...** button.
   - Navigate to the folder and select the `manifest.json` file.
4. **Usage**:
   - The extension is now active. Refresh any open tabs to see the changes take effect.
   - *Note: Temporary add-ons are removed when Firefox restarts.*

## Support this Project

If you find this extension useful, you can support its development on Ko-fi:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/fearlessgeekmedia)

## Example

![Example of the extension in action](example.png)

## How it Works

The extension uses a `MutationObserver` to watch for new content being added to the page (like in social media feeds or infinite scrolling sites) and performs a case-sensitive replacement of the target terms.

# Default Tab Icon

Replaces the empty tab icon with a simple browser icon.

When a page has no favicon, [Zen Browser](https://zen-browser.app/) shows a blank placeholder in the tab. This mod replaces it with a clean browser icon, so tabs without a favicon are easy to recognize. The icon follows your theme colors automatically.

---

![image](image.png)

---

## Installation

### Zen Mods (recommended)

1. Open Zen settings → **Zen Mods**.
2. Find **Default Tab Icon** and click **Install**.
3. Restart Zen if the icon doesn't appear right away.

### Manual

1. Open `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
2. Open `about:support` and click **Open Folder** next to **Profile Folder**.
3. Create a `chrome` folder in it if it doesn't exist.
4. Copy the contents of [`chrome.css`](chrome.css) into `chrome/userChrome.css`. Create the file if needed.
5. Restart Zen completely.

If nothing changes, clear the startup cache: `about:support` → **Clear startup cache**.

## Customization

The icon is the built-in `chrome://global/skin/icons/defaultFavicon.svg`. To use another one, replace that URL in [`chrome.css`](chrome.css).

## Changelog

Version 1.0.0

- First release.

## License

[MIT](LICENSE)

## Schemer

Schemer is a plugin for Obsidian (https://obsidian.md).

URL schemes provide tools for customizable automation between apps. When you launch a URL scheme by invoking a Schemer command, it uses data from your Obsidian notes and takes some action in the destination app.

Add new URL schemes for Schemer in the plugin's preferences. Then, invoke the new scheme from the Command Palette (default hotkey: <kbd>cmd/ctrl</kbd>+<kbd>p</kbd>). (You can also assign a custom hotkey to the newly added scheme in Preferences → Hotkeys.)

Note: to use URL schemes, an app must have implemented the option—in other words, not every app will work with URL schemes.

### Manually installing the plugin

- Copy over `main.js`, `styles.css`, `manifest.json` to your vault `VaultFolder/.obsidian/plugins/your-plugin-id/`.

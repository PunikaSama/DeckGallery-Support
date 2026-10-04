# DeckGallery Support

Support for the DeckGallery Stream Deck plugin by **PunisherSama**.

Display your pictures across your Stream Deck image keys. Create albums with individual crops and automatic image changes. Press any image key to return.

## Setup

1. Install DeckGallery with Stream Deck 7.1 or newer and put **Open Wallpaper** on your home page.
2. Select the key. Under **Images**, choose static PNG, JPEG or WebP files (up to 25 MB and 40 million pixels each).
3. Set a name under **Profile** and select **Create profile**. Changes to existing profiles save automatically; wait for **Saved** before closing the settings.
4. Add, replace, reorder and remove images under **Images**. **Fill** sizes automatically; **Adjust** lets you drag and resize. The preview uses the device of the edited key.
5. Under **Slideshow**, enable automatic changes with an interval from 5 seconds to 24 hours and optional shuffle. With one picture or with the switch off, the picture stays static.
6. Press the wallpaper key. Confirm installation of the bundled display template if prompted. Any image key returns and stops the slideshow.

## Support

[Open a GitHub Issue](https://github.com/PunikaSama/DeckGallery-Support/issues/new) for problems or feature requests. Include the plugin version, Stream Deck software version, device model, operating system and steps to reproduce the problem. Remove private pictures and personal information from attachments.

Private support: **support@punishersama.de**.

## Privacy

Last updated: 4 October 2026. Maintainer: **PunisherSama**. Contact: **support@punishersama.de**.

DeckGallery processes pictures locally. The plugin does not upload images, collect analytics, create accounts or run an external network service. It connects to Stream Deck through the local WebSocket interface.

Original images, normalized copies, albums, image order, crops, viewing intervals, device assignments and cached key images are stored on your computer. Originals may contain EXIF metadata. Your explicitly selected language is remembered in local editor storage.

Data directories retain the original project name for update compatibility:

- Windows: `%APPDATA%\CustomDeckWallpaper`
- macOS: `~/Library/Application Support/CustomDeckWallpaper`

Deleting a profile removes its entry; image files may remain because other profiles can use them. To remove all plugin data, stop the plugin and remove the data directory. Uninstalling the plugin does not automatically remove it.

Support messages are used to handle your request. GitHub Issues are public and operated by GitHub. Avoid posting private pictures or personal data there. For deletion of private support correspondence, contact the address above. GitHub, email-provider services and Elgato Marketplace purchases, updates and licensing are governed by their providers.


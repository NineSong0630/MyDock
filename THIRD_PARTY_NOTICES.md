# Third-party notices

MyDock is built with, and ships with, the open-source software listed below. Each component remains under its own licence and belongs to its authors. Thank you to all of them.

## Bundled programs

### Rainmeter 4.5.28.3936

- Website: https://www.rainmeter.net/
- Licence: GNU General Public License v2.0 — https://github.com/rainmeter/rainmeter/blob/master/LICENSE
- Copyright © Rainmeter Project Developers
- Source code of this exact version: https://github.com/rainmeter/rainmeter/releases/tag/v4.5.28.3936
- MyDock ships the official Rainmeter binaries and its default *illustro* skins, **unmodified**, in the `engine` folder of the install directory. They're used to run `.rmskin` skins that users download themselves. MyDock doesn't link against Rainmeter; it starts it as a separate program.

## Libraries in the MyDock app

| Component | Licence | Source |
|---|---|---|
| Qt 6 / PySide6 (Qt for Python) | LGPL-3.0 | https://code.qt.io/cgit/pyside/pyside-setup.git/ · https://www.qt.io/ |
| Python | PSF License | https://www.python.org/ |
| NumPy | BSD-3-Clause | https://github.com/numpy/numpy |
| psutil | BSD-3-Clause | https://github.com/giampaolo/psutil |
| pywin32 | PSF License | https://github.com/mhammond/pywin32 |
| comtypes | MIT | https://github.com/enthought/comtypes |
| pycaw | MIT | https://github.com/AndreMiras/pycaw |
| PyWinRT (`winrt-*`) | MIT | https://github.com/pywinrt/pywinrt |
| PyInstaller bootloader | GPL-2.0 with the bootloader exception | https://github.com/pyinstaller/pyinstaller |
| Inno Setup (installer) | Inno Setup License | https://jrsoftware.org/isinfo.php |

**About Qt / PySide6 (LGPL-3.0):** MyDock uses the unmodified Qt and PySide6 libraries as separate DLL / `.pyd` files in the install folder. You may replace them with your own compatible build. The LGPL-3.0 text is at https://www.gnu.org/licenses/lgpl-3.0.html and the GPL-3.0 text it refers to is at https://www.gnu.org/licenses/gpl-3.0.html.

## Online services

These services are only contacted when you use the related feature (see *Privacy* in the README):

- **Open-Meteo** — weather and city search. Data licensed under CC BY 4.0. https://open-meteo.com/
- **LRCLIB**, **NetEase Cloud Music**, **QQ Music** — lyrics lookup. Lyrics belong to their rights holders. MyDock only shows them on your screen.
- **YouTube Data API** — optional full shuffle, using the user's own API key, under the YouTube API Services Terms of Service. https://developers.google.com/youtube/terms
- **GitHub API** — checking for updates.

## Built-in skin designs

The built-in desktop skins are MyDock's own drawings. Their layouts are inspired by these Rainmeter skins, and no files from them are used. The authors are credited inside the app and in the README:

- *Mond* by HipHopium — https://www.deviantart.com/hiphopium
- *Irena* by ApexXx-SenSei — https://www.deviantart.com/apexxx-sensei
- *Inside Dream* by Nasirivand — https://www.deviantart.com/nasirivand
- *Shadow Clock* by SugMadik — https://www.deviantart.com/sugmadik

If you are one of these authors and want something changed or removed, please open an issue: https://github.com/NineSong0630/MyDock/issues

## Trademarks

Windows is a trademark of Microsoft. YouTube is a trademark of Google LLC. Spotify is a trademark of Spotify AB. Rainmeter and all other names are the property of their respective owners. MyDock is not affiliated with or endorsed by any of them.

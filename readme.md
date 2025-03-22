<a name="readme-top"></a>

# Template for Creating Chromium-based Web Browser Theme

Template repository for customizing your browsing experience by designing your unique Chromium-based web browser
theme from scratch.

> [!TIP]
>
> ⭐ ⭐ ⭐ Star This Repository ⭐ ⭐ ⭐
>
> If you find this theme template and my work useful, please consider supporting me giving a ⭐ star ⭐ to this
> repository, and [follow me on GitHub](https://github.com/iamprogrammerlk).

## Install

### Get it from web store(s)

<!--

- [Google Chrome Web Store](https://chromewebstore.google.com/detail/__ID__)

-->

### Install it manually

First, download the latest released ZIP file from the [releases section](/../../releases) and save it to your computer.
Then, unzip the file and follow the instructions below, which may vary slightly depending on your browser:

- To access the Extension Management page, visit the following URL: [chrome://extensions](chrome://extensions).
  You can also open the Extension Management page by clicking on your browser's menu and
  selecting `Extensions -> Manage Extensions`.

- To enable "Developer mode," select the option located at the top right corner of the page.

- Click the `Load unpacked` button, then find the directory where you extracted the release and select it.

- The theme should now be active in your browser. To remove the theme, access your browser's theme or appearance
  settings and select a different one.

<!--

## Screenshots

![screenshot_01_1280x800_active](/resource/screenshot/screenshot_01_1280x800_active.png)
![screenshot_02_1280x800_inactive](/resource/screenshot/screenshot_02_1280x800_inactive.png)
![screenshot_03_1280x800_incognito](/resource/screenshot/screenshot_03_1280x800_incognito.png)
![screenshot_04_1280x800_appearance](/resource/screenshot/screenshot_04_1280x800_appearance.png)
![screenshot_05_1280x800_search](/resource/screenshot/screenshot_05_1280x800_search.png)

-->

## List of Chromium-based Web Browsers

| Browser                       | Tested | Theme Supported | Browser Developer    |
| ----------------------------- | ------ | --------------- | -------------------- |
| [Google Chrome][chrome]       | ✅     | ✅              | Google               |
| [Microsoft Edge][edge]        | ✅     | ✅              | Microsoft            |
| [Ungoogle Chromium][chromium] | ✅     | ✅              | Slimjet              |
| [Vivaldi][vivaldi]            | 🔴     | ☑️              | Vivaldi Technologies |
| [Opera][opera]                | 🔴     | ☑️              | Opera Software       |
| [Brave][brave]                | 🔴     | ☑️              | Brave Software       |
|                               |        |                 |                      |

- ✅ Tested/Supported

- ☑️ Should work in theory

- 🔴 Not Tested

> [!NOTE]
>
> This theme uses `Manifest V3` to ensure compatibility with the latest Chromium extension standards.

## A sample of the `manifest.json` file containing all supported properties.

```json
{
  "author": "I am Programmer <contact@iamprogrammer.lk>",
  "description": "Chrome theme by I am Programmer",
  "icons": {
    "128": "image/store_icon_128x128.png"
  },
  "manifest_version": 3,
  "name": "Simple Theme",
  "short_name": "simple_theme",
  "theme": {
    "colors": {
      "control_background": [0, 0, 0],
      "control_button_background": [0, 0, 0],
      "background_tab": [0, 0, 0],
      "background_tab_inactive": [0, 0, 0],
      "background_tab_incognito": [0, 0, 0],
      "background_tab_incognito_inactive": [0, 0, 0],
      "bookmark_text": [0, 0, 0],
      "button_background": [0, 0, 0],
      "frame": [0, 0, 0],
      "frame_inactive": [0, 0, 0],
      "frame_incognito": [0, 0, 0],
      "frame_incognito_inactive": [0, 0, 0],
      "ntp_background": [0, 0, 0],
      "ntp_header": [0, 0, 0],
      "ntp_link": [0, 0, 0],
      "ntp_link_underline": [0, 0, 0],
      "ntp_text": [0, 0, 0],
      "ntp_section": [0, 0, 0],
      "ntp_section_link": [0, 0, 0],
      "ntp_section_link_underline": [0, 0, 0],
      "ntp_section_text": [0, 0, 0],
      "omnibox_background": [0, 0, 0],
      "omnibox_text": [0, 0, 0],
      "tab_background_text": [0, 0, 0],
      "tab_background_text_inactive": [0, 0, 0],
      "tab_background_text_incognito": [0, 0, 0],
      "tab_background_text_incognito_inactive": [0, 0, 0],
      "tab_text": [0, 0, 0],
      "toolbar": [0, 0, 0],
      "toolbar_button_icon": [0, 0, 0],
      "toolbar_text": [0, 0, 0]
    },
    "images": {
      "theme_frame": "images/theme_frame.png",
      "theme_frame_inactive": "images/theme_frame_inactive.png",
      "theme_frame_incognito": "images/theme_frame_incognito.png",
      "theme_frame_incognito_inactive": "images/theme_frame_incognito_inactive.png",
      "theme_frame_overlay": "images/theme_frame_overlay.png",
      "theme_frame_overlay_inactive": "images/theme_frame_overlay_inactive.png",
      "theme_toolbar": "images/theme_toolbar.png",
      "theme_ntp_background": "images/theme_ntp_background.png",
      "theme_tab_background": "image/theme_tab_background.png",
      "theme_tab_background_incognito": "images/theme_tab_background_incognito.png",
      "theme_tab_background_inactive": "images/theme_tab_background_inactive.png",
      "theme_tab_background_incognito_inactive": "images/theme_tab_background_incognito_inactive.png",
      "theme_ntp_attribution": "images/theme_ntp_attribution.png",
      "theme_button_background": "images/theme_button_background.png",
      "theme_window_control_background": "images/theme_window_control_background.png"
    },
    "tints": {
      "background_tab": [0, 0, 0],
      "buttons": [0, 0, 0],
      "frame": [0, 0, 0],
      "frame_inactive": [0, 0, 0],
      "frame_incognito": [0, 0, 0],
      "frame_incognito_inactive": [0, 0, 0]
    },
    "properties": {
      "ntp_background_alignment": "bottom",
      "ntp_background_repeat": "repeat",
      "ntp_logo_alternate": 1
    }
  },
  "version": "1.0.0",
  "version_name": "simple_theme_v1.0.0"
}
```

> [!IMPORTANT]
>
> Chromium has discontinued the use of "ntp_section," but it still utilizes it as a fallback option for "ntp_header" in
> order to support legacy themes.
>
> ```
> {
>  "theme": {
>    "colors": {
>      "ntp_section": [0, 0, 0],
>    }
>  }
> }
> ```

Please remove all unused properties from the `manifest.json` file. If you use `images`, make sure that the image file
exists at the path and that the image dimensions are correct.

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# 🧰 Resource

- The list of properties supported by the Chromium browser has been extracted from this source.

  - https://source.chromium.org/chromium/chromium/src/+/main:chrome/browser/themes/browser_theme_pack.cc

- Theme Creation Guide By Patrick Batenburg

  - https://github.com/Patrick-Batenburg/GoogleChromeThemeCreationGuide

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# 💕 Credits

- I am Programmer [@iamprogrammerlk](https://github.com/iamprogrammerlk)

  [iamprogrammer.lk](https://iamprogrammer.lk)
  🔸 [contact@iamprogrammer.lk](mailto:contact@iamprogrammer.lk)
  🔸 [x.com/iamprogrammerlk](https://x.com/iamprogrammerlk)
  🔸 [youtube.com/@iamprogrammerlk](https://youtube.com/@iamprogrammerlk)

- [Contributors](/../../graphs/contributors)

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# ✨ Get Involved

Get in touch with the project developers and the community through our [GitHub Discussions](/../../discussions) forum.
View [contributing.md](/contributing.md) for information.

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# 🔥 Issues

Bug reports and feature requests can be submitted on the [Github Issues](/../../issues).

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# 👍 Code of Conduct

This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to
the [Code of Conduct](/code_of_conduct.md), [Security Policy](/security.md), and be bound by the terms of the
[Contributor License Agreement](/contributor_license_agreement.md).

> [!IMPORTANT]
>
> This project is not a platform for discussing politics, social issues, race, religion, gender, or sexual
> orientation. Please keep those discussions elsewhere.

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# ⚖️ License

### This work is distributed under the [MIT License](https://choosealicense.com/licenses/mit/) License.

See [license](/license.md) for more information.

### Permissions

- ✅ Commercial use
- ✅ Distribution
- ✅ Modification
- ⛔ ~~Patent use~~
- ✅ Private use

### Conditions

- ⛔ ~~Disclose source~~
- ✅ License and copyright notice
- ⛔ ~~Network use is distribution~~
- ⛔ ~~Same license~~
- ⛔ ~~State changes~~

### Limitations

- 🚫 Liability
- ⛔ ~~Trademark use~~
- 🚫 Warranty

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# ©️ Copyright

- Copyright © 2025 🇱🇰 I am Programmer [@iamprogrammerlk](https://github.com/iamprogrammerlk).
- Copyright © 2025 ❤️ [Contributors](/../../graphs/contributors).

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

[chrome]: https://www.google.com/chrome/
[edge]: https://www.microsoft.com/en-us/edge
[chromium]: https://github.com/ungoogled-software/ungoogled-chromium
[vivaldi]: https://vivaldi.com/
[opera]: https://www.opera.com/
[brave]: https://brave.com/

![Build Status](https://github.com/paveyry/better-hangoutschat/actions/workflows/build.yml/badge.svg)

Better Google Spaces (former Hangouts Chat)
======================================================

This patch extends Google Hangouts Chat to make it nicer and simpler to use.
Works with both the web browser version and the standalone Chrome App.

In order to use the dark theme, GMail or GHC should already be in dark mode.
In order to use the light theme, GMail or GHC should already be in light (default) mode.
This plugin will alter some of the color-scheme but relies on the existing color modes.

*Note*: To use this plugin in the standalone GHC Chrome App, you can use the Chrome 
version of the extension within Chrome (more details below). The features will apply within
the Chrome App exactly like they would in the browser.

Features
---------

Current features: 

- Smaller margins and buttons for better readability and screen space optimization
- Wider and more adaptive thread right-side panel
- Thread-link buttons at the top of each thread for easier referencing
- Several different variants:
    - Light theme (Chat standard colors)
    - Slack theme
    - Dark theme

Installing from official release files
---------------------------------------

### Using the Firefox extension (recommended)

- Download the `firefox-better_hangouts_chat_<theme>_X.X.X.xpi` file of your choice from the 'releases' section: <https://github.com/paveyry/better-hangoutschat/releases>
- Open it with Firefox to install the extension and follow the instructions.
- Enjoy

### Using the Chrome extension (not signed by Google)

- Download the `chrome-better_hangouts_chat_<theme>_X.X.X..zip` file of your choice from the 'releases' section: <https://github.com/paveyry/better-hangoutschat/releases>
- Unzip the archive
- In Chrome, open <chrome://extensions>
- Click "Developer mode" at the top right-hand corner
- Click "Load unpacked" and select the directory extracted from the zip archive
- Enjoy


Building script from source
----------------------------

Just run this command:

    ./generate_patch.sh

The output will appear in the `out` directory.

Preview
--------

### Thread links
![Screenshot](https://user-images.githubusercontent.com/3884900/88812353-88091500-d1af-11ea-8d3d-579cab4aa143.png)

Click on the *Show Thread Links* button and thread links will appear before each thread in the current window.

![Screenshot](https://user-images.githubusercontent.com/3884900/112030582-5247e080-8b32-11eb-8280-3fe396da923e.png)

### Dark Theme
![Screenshot](https://user-images.githubusercontent.com/3884900/63685721-01f28a80-c7f8-11e9-8522-75446596d574.png)

### Slack Theme
![Screenshot](https://user-images.githubusercontent.com/3884900/63689984-6c5cf800-c803-11e9-864e-ec578353b946.png)

### Light Theme
![Screenshot](https://user-images.githubusercontent.com/3884900/63689983-6c5cf800-c803-11e9-8857-53326ec1d22b.png)

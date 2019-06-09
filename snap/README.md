# Unofficial Snap Packaging for FeatherPad
<!--
	Use the Staticaly service for easy access to in-repo pictures:
	https://www.staticaly.com/
-->
<img src=gui/featherpad.svg alt='Icon of FeatherPad' width=256px title='Icon of FeatherPad' />

**This is the unofficial snap for FeatherPad**, *"Lightweight Qt5 Plain-Text Editor for Linux"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![Build Status Badge of the `featherpad` Snap](https://build.snapcraft.io/badge/Lin-Buo-Ren/featherpad-snap.svg "Build Status of the `featherpad` snap")](https://build.snapcraft.io/user/Lin-Buo-Ren/featherpad-snap)

![Screenshot of the Snapped Application](local/screenshots/main-interface.png "Screenshot of the Snapped Application")

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### In a Terminal
    # Install the snap #
    sudo snap install featherpad
    
    # Connect the snap to optional security confinement interfaces #
    ## For loading/saving files under `/mnt` and `/media` ##
    sudo snap connect featherpad:removable-media
    
    # Launch the application #
    featherpad
    snap run featherpad # If you have another existing installation

### The Graphical Way
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/featherpad)

## What is Working
* Launch application
* Load/Save file
* I18N
* Syntax highlighting
* Showing help text
* About dialog
* Showing line number
* Changing editor font

## What is NOT Working...yet 
Check out the [issue tracker](https://github.com/Lin-Buo-Ren/featherpad-snap/issues) for known issues.

## Support
* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/Lin-Buo-Ren/featherpad-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>

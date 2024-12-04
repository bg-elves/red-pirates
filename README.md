# Red Pirates Browser

## Overview

A revolutionary tool for maintaining online anonymity and independence, designed to combat Russian troll activity.

## Features
### Key Highlights

* Tor Network Integration: Leverages the Tor network for enhanced anonymity
* Multi-Session Management: Supports running multiple independent browsers simultaneously, each with its own session data
* Fingerprinting Protection: Covers 90% of common fingerprinting methods used by trackers and advertisers

## How it Works

### Prerequisites

The software will take care of most of the things you need to run it on any OS.
However, due to the lack of time to prepare everything for this release, you need to do a few manual steps:

* The Tor Bundle is not part of the software installation yet, so in order to use it to the max, please install Tor manually. If you like, you can configure any available port on your machine, you can change it in the UI. If you don't make any changes to the torrc, than it will try to connect to the default 9050 port.

* MacOS permissions need special care. Since we build our browser upon Brave source builds, we need special permission to the Accessability and Screen Recording, during setting up the first run. Our software will inform you and will open the corresponding settings for you, if needed. Please note, once a error message is shown, you need to clear it from toolbar menu -> `Data` -> `Reset error state` before you can try again. The software doesn't record your screen, nor your keyboard, the permissions are required because we use different techniques to prepare the browser for best experience and we manage a few windows in the background during setup. After a successful setup, those permissions are no longer needed and can be removed.

### Getting started

####  Obtain a passkey from our Discord server. Passkeys will refresh every month, so you need to be active, in order to get a working passkey

* Download the latest release for your OS from GitHub [Releases](https://github.com/bg-elves/red-pirates/releases) and install it
* The software will take care of the rest of the tools
* Launch Red Pirates Browser to begin using it for secure browsing and session management
* Create a new browser instance or resume an existing one
* Support and Community


## Visit [Red Pirates](https://discord.com/invite/72gcvShPWZ) Discord Server
Report any bugs or issues to our support team for prompt resolution
Disclaimer

By using Red Pirates Browser, you acknowledge that you understand the potential risks associated with online anonymity. We recommend exercising caution when browsing sensitive information.

# Troubleshooting and uninstallation

* Error messages can be cleaned from the toolbar menu -> `Data` -> `Reset error state`.
* If the initial setup fails for some reason and you need to repeat it, click toolbar menu -> `Data` -> `Clear Brave Default data`
* Note: When the Brave build is downloaded, we use a caching mechanism, so that it doesn't download it again if needed. This is required during testing, to reduce bandwidth and time to run. After our software is setup, you can remove the cached one from `Data` -> `Clear Brave Cache data`, it will save you a few hundred MB's.

### In case you want to remove the software, first
1. `Data` -> `Clear Brave Temp data`
2. `Data` -> `Clear Brave Cache data`
3. `Data` -> `Open storage folder` and delete the opened folder
4. Proceed with uninstallation as usual on your OS
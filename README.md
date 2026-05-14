# DNDWhitelist

Adds an option to the user context menu to whitelist users while you are in Do Not Disturb mode.

Whitelisted users can still trigger notification sounds and call sounds in non-muted channels even when your status is set to DND.

![Screenshot](./screenshot.png)

## Features

- Add or remove users from a DND whitelist directly from the user context menu
- Receive notification sounds from whitelisted users while in DND
- Receive incoming call sounds from whitelisted users while in DND
- Respects muted channels (notifications only play in non-muted channels)

## Current Limitations

- Incoming calls currently only play a sound
- The incoming call popup / answer UI is still planned and not implemented yet

## Installation

See [here](https://github.com/D3SOX/vencord-userplugins#install) and the [Vencord docs for installing custom plugins](https://docs.vencord.dev/installing/custom-plugins/)

## Usage

1. Right click a user
2. Select:
   - `Add to DND whitelist`
   - or `Remove from DND whitelist`
3. While in DND mode, notifications and calls from whitelisted users will still play sounds

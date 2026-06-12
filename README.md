# VIPER ELITE

A Logitech G Hub script designed for Rainbow Six Siege.

## Features

* Recoil Compensation
* RapidFire
* SpamCrouch
* Multiple Scope Support
* Customizable Settings
* Lightweight and Easy to Configure

## Requirements

* Logitech G Hub
* Supported Logitech Mouse
* Rainbow Six Siege

## Setup

Before using the script, you **must** enter your personal settings into the configuration section of the script.

Locate the following section:

```lua
-- YOUR SETTINGS
YourMouseModel = "PLACEHOLDER"  -- G Pro Superlight, G Pro, G502, G903, G403, G305, G703, G604, G309, G203
YourDPI        = -999  -- Your mouse DPI
YourHorizSens  = -999  -- Your horizontal sensitivity
YourVertSens   = -999  -- Your vertical sensitivity
UserFOV        = -999  -- Your in-game FOV
SensMultiplier = -999  -- Your MouseSensitivityMultiplierUnit (Default: 0.02)

AdvancedADSMultipliers = {
    ["1x"]   = -999, -- Your 1x scope sensitivity
    ["2.5x"] = -999, -- Your 2.5x scope sensitivity
}
```

Replace every placeholder value with your own Rainbow Six Siege settings.

### Example

```lua
YourMouseModel = "G Pro Superlight"
YourDPI        = 800
YourHorizSens  = 8
YourVertSens   = 8
UserFOV        = 90
SensMultiplier = 0.02

AdvancedADSMultipliers = {
    ["1x"]   = 35,
    ["2.5x"] = 50,
}
```

## Support

If you need assistance with setup, custom keybinds, or script modifications, contact:

Discord: Kyrje__

## Disclaimer

Users are responsible for ensuring that their use of this script complies with the rules and terms of service of any game, software, or platform.

## Author

Created by Kyrje

© 2026 Kyrje. All rights reserved.

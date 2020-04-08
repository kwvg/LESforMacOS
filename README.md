![Live Enhancement Suite](https://raw.githubusercontent.com/itsbartsimpson/LESforMacOS/master/Hammerspoon/Images.xcassets/AppIcon.appiconset/icon_256x256.png)

## What is the HSModule?

HSModule is the secret voodoo magic that powers the Live Enhancement Suite on Mac. 

Basically, its a bunch of Lua scripts that leverage the capabilities of Hammerspoon (which is what LES for macOS is based on) to speed up your Ableton Live workflow.

## What are all these files?

| Name                                                    | Purpose                                                      |
| ------------------------------------------------------- | ------------------------------------------------------------ |
| `LESMain.lua`                                           | The heart of LES, this is the actual Lua script that drives the Live Enhancement Suite |
| `setup.lua`                                             | Its a setup file                                             |
| `init.lua`                                              | This is first file that runs whenever LES starts             |
| `Resources/Configurations/menuconfig.ini`               | The default menu configuration file that is placed in every new LES install |
| `Resources/Configurations/settings.ini`                 | The default settings file that is placed in every new LES install |
| `Resources/Configurations/live.enhancement.suite.plist` | This is the file that tells macOS to add LES as an autostarting application (if the user wants that) |
| *Everything Else that isn't GitHub related or legal*    | Just some little fun                                         |

## Sounds cool, how can I help?

* Read our [Contributing Guidelines](https://github.com/LiveEnhancementSuite/LESforMacOS/blob/master/CONTRIBUTING.md) and [Code of Conduct](https://github.com/LiveEnhancementSuite/LESforMacOS/blob/master/CODE_OF_CONDUCT.md) and get started contributing to the LES module
* Donate your couch pennies to help fund the development of LES with [PayPal](https://paypal.me/enhancementsuite)

# midi-sammi-extension
Control sammi with a midi device

This won't work inside an obs dock until this issue is resolved: https://github.com/obsproject/obs-browser/issues/195

**I REPEAT. YOU MUST OPEN SAMMI'S BRIDGE IN AN EXTERNAL BROWSER FOR THIS TO WORK**

## Usage

Do not have your sammi bridge docked, instead open it up in any modern browser of your choice.

For your button use the extension trigger.

There are four triggers you can use:
* `Midi Note On`
* `Midi Note On NOTE`
* `Midi Note Off`
* `Midi Note Off NOTE`

`NOTE` can be replaced with any valid midi note, for example `C3` or `F#4`. It starts at `C0` and works up to `C8` (I think). 

All the black keys are using Sharps instead of flats so please be aware.

Every trigger has a `note` property that you can pull to get whatever note was pressed.  Similarly, there is a `velocity` property that you can pull as well.

### Setting Up Variables

In the deck that is created when the extension is installed, there is a button called `midiVariables`. In it, it sets several variables that the extension uses. It runs on sammi startup, but can also be ran manually if you want to change the values. Please note that the extension polls every 10 seconds for a value change.

* `debug` - determines if logging is output to the console. If you contact the developer, please turn this on and send the console logs so I can know what's happening.
* `velocityThreshold` - the minimum velocity that has to be met before `Midi Note On` will be triggered. This can be used to make the keys/pads less sensitive. 

## Contact

If you have any bugs or suggestions feel free to open an issue here. You can reach me on twitter at swolekat1 I also stream on twitch at swolekat



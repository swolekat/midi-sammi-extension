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

Every trigger has a `note` property that you can pull to get whatever note was pressed. 

## Contact

If you have any bugs or suggestions feel free to open an issue here. You can reach me on twitter at swolekat1 I also stream on twitch at swolekat



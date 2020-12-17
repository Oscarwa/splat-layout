# splat-layout

Streaming layout for splat shoots

## Changelog

* 2020-11-01 - launch beta version

## Usage

Use this as a Web Resource on OBS or your preferred streaming software

Make sure to setup your channel name on URL

https://oscarwa.github.io/splat-layout?channel=nazgulmx

Or use it with the available options

https://oscarwa.github.io/splat-layout?channel=channelName&command=command&min=min&max=max

Where:
* `channelName` ***(required)*** - Can be a single channel (e.g. `channel=nazgulmx`) or a series of channels comma separated (e.g. `channel=nazgulmx,twitch,nintendo`) 
* `command` ***(optional - default: splat)*** - The command you want to use on your channel (e.g. `command=shoot`) this will allow users to use the command on your chat
* `min` ***(optional - default: 5)*** - The minimum number of shots per command 
* `max` ***(optional - default: 8)*** - The maximum number of shots per command 
* `vol` ***(optional - default: 0.2)*** - A value from 0.0 to 1.0 to set the volume of the shoots
  
*TIP: To always get the same number of shoots set min and max to the same value (e.g. `min=3&max=3`)*


## License
[MIT](https://choosealicense.com/licenses/mit/)

# splat-layout

Streaming layout for splat shoots and squids on screen

## Changelog

* 2020-11-01 - launch beta version
* 2021-03-09 - Added multisquid support
* 2021-03-12 - Added statistics command
* 2021-04-01 - Added more config variables

## Usage

Use this as a Web Resource on OBS or your preferred streaming software

A typical URL (browser source) should look like this:

https://oscarwa.github.io/splat-layout?channel=nazgulmx

That will give your chat the following commands:

`!splat` - User will trigger an animation and sound of several (5 to 8) splats on screen, if the user has a color set up for his name, splat shoots will appear that color.
`!squid` - User will spawn a squid (random color) on screen swimming around, user name will appear in squid face.
`!splat_stats` - Bot will show all the statistics for the session in the following format: 
`[Splat stats] Total shoots: 17 | Total squids: 5 | Most splatted by: NazgulMX [1] | Most squids by: NazgulMX [5] | Most shoots by: NazgulMX [12]`


Some options are configurable, you just need to include them in your URL:
* `channelName` ***(required)*** - Can be a single channel (e.g. `channel=nazgulmx`) or a series of channels comma separated (e.g. `channel=nazgulmx,twitch,nintendo`) 
* `command` ***(optional - default: splat)*** - The command you want to use on your channel (e.g. `command=shoot`) this will allow users to use the command on your chat
* `max_squids` ***(optional - default: 3)*** - Maximum number of simultaneous squids on screen
* `cooldown` ***(optional - default: 1)*** - A value in seconds of cooldown between shoots command (This will prevent shoots to appear on screen but won't prevent users to spam shoot command)
* `min` ***(optional - default: 5)*** - The minimum number of shots per command 
* `max` ***(optional - default: 8)*** - The maximum number of shots per command 
* `vol` ***(optional - default: 0.2)*** - A value from 0.0 to 1.0 to set the volume of the shoots
  
*TIP: To always get the same number of shoots set min and max to the same value (e.g. `min=3&max=3`)*


## License
[MIT](https://choosealicense.com/licenses/mit/)

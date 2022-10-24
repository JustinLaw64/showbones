# showbones-ng

### A mod for [Minetest](http://www.minetest.net)

This mod saves the locations of player bones in the mod storage database. Players can use the chat command `/showbones` to show waypoints to their bones.

If a player has left more than the server limit (default 3) of bones lying around the world, the oldest ones are removed from the world as the new one is created. Waypoints are numbered 1 - server limit. The newest/latest bones would be 1. Bones waypoints may be hidden by using the /showbones chat command again.

If a player wants to clear old waypoints, it can be done using /clearbones chat command. It will remove ALL existing bone waypoints for that player.
 
This mod was created in hopes relieving the frustration of players and admins trying to locate lost bones. There is also the added bonus that server admins will no longer need to clean up messy, discarded bones from all around the server. 


## License: LGPL 2.1

## Credits 

* [Justin](https://github.com/JustinLaw64/) modified this mod to where it no longer deletes old bones and provokes owners.
* PilzAdam - The creator of the bones mod. Some code copied (on_punch function) for a needed override.

## Features

* Adds chat command: /showbones
* Adds privilege: None at this time
* Dependencies: bones
* Original's Post: [Original forum post](https://forum.minetest.net/viewtopic.php?f=9&t=15453)
* Forum link: [WIP forum post](https://forum.minetest.net/viewtopic.php?f=9&t=15453)
* Known bugs: Look to the original.

![screenshot_20160919_212218](https://cloud.githubusercontent.com/assets/9083807/18654745/85df0a5a-7eb1-11e6-8071-3d736b13b435.png)


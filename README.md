# showbones-ng

### A mod for [Minetest](http://www.minetest.net)

This mod saves the locations of player bones in the mod storage database. Upon death, the player is shown the location of their bones in the HUD. They can use `/hidebones` to hide the bones HUD, and `/showbones` to show the bones HUD.

If a player has left more than the server limit (default 3) of bones lying around the world, the oldest ones are removed from the world as the new one is created.

If a player wants to clear old waypoints, it can be done using /clearbones chat command. It will remove ALL existing bone waypoints for that player.
 
This mod was created in hopes relieving the frustration of players and admins trying to locate lost bones. There is also the added bonus that server admins will no longer need to clean up messy, discarded bones from all around the server. 

## Features

* Adds chat commands: `/showbones`, `/hidebones`, and `/clearbones`
* Dependencies: bones
* Original Forum Post: [Original forum post](https://forum.minetest.net/viewtopic.php?f=9&t=15453)

![screenshot_20160919_212218](https://cloud.githubusercontent.com/assets/9083807/18654745/85df0a5a-7eb1-11e6-8071-3d736b13b435.png)

## Credits 

* [Justin](https://github.com/JustinLaw64/) modified this mod to where it no longer deletes old bones and provokes owners.
* PilzAdam - The creator of the bones mod. Some code copied (on_punch function) for a needed override.




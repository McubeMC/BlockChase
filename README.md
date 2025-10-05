

## Introduction
BlockChase est un mode de jeu revisité du mini-jeu "BlockHunt" ou "Prophunt", qui sont eux même une version revisité du mode de jeu "Hide and seek"".
Ce mode de jeu permet au joueur de ce transformer en bloc afin de se cacher des chercheurs. This plugin allows you to do that but with a lot more features added on such as: shops, stats etc...

### Dependency : ([Lib's Disguises](https://www.spigotmc.org/resources/libs-disguises.81/) and [ProtocolLib](http://dev.bukkit.org/bukkit-plugins/protocollib/))

## Features
* Custom wand for selection arena.
* Multiple arenas.
* **Join/Leave signs!**
* Arena full bypass.
* Configurable blocks.
* **Solid blocks like the Hives!**
* Enable commands per arena.
* Executing commands on win.
* **Shop with tokens!**
* Instant respawn.
* **_And more!_**

## MCStats
[![](http://api.mcstats.org/signature/blockhunt.png)](http://mcstats.org/plugin/BlockHunt/)

## Commands & Permissions
_**Note:** Instead of using /BlockHunt you could use:_
* /bh
* /hideandseek
* /seekandfind (from my old plugin)

<> = Required [] = Optional

|Command|Description|Permission||
|:--|:--|:--|:--|
|`/BlockHunt [info/i]`|Displays the plugin's info.|blockhunt.info|_All players have this permission from default._|
|`/BlockHunt <help/h>`|Shows a list of commands.|blockhunt.help|_All players have this permission from default._|
|`/BlockHunt <reload/r>`|Reloads all configs.|blockhunt.reload|blockhunt.admin|
|`/BlockHunt <join/j> <arenaname>`|Joins a BlockHunt game.|blockhunt.join|blockhunt.player|
|`/BlockHunt <leave/l>`|Leave a BlockHunt game.|blockhunt.leave|blockhunt.player|
|`/BlockHunt <list/li>`|Shows a list of available arenas.|blockhunt.list|blockhunt.player|
|`/BlockHunt <shop/sh>`|Opens the BlockHunt shop.|blockhunt.shop|blockhunt.player|
|`/BlockHunt <start/go> <arenaname>`|Forces an arena to start.|blockhunt.start|blockhunt.moderator|
|`/BlockHunt <wand/w>`|Gives you the wand selection tool.|blockhunt.create|blockhunt.admin|
|`/BlockHunt <create/c> <arenaname>`|Creates an arena from your selection.|blockhunt.create|blockhunt.admin|
|`/BlockHunt <set/s> <arenaname>`|Opens a panel to set settings.|blockhunt.set|blockhunt.moderator|
|`/BlockHunt <setwarp/sw> <lobby/hiders/seekers/spawn> <arenaname>`|Sets warps for your arena.|blockhunt.setwarp|blockhunt.moderator|
|`/BlockHunt <remove/delete> <arenaname>`|Deletes an Arena.|blockhunt.remove|blockhunt.admin|
|`/BlockHunt <tokens/t> <set/add/take> <playername> <amount>`|Change someones tokens.|blockhunt.tokens|blockhunt.admin|
||Able to join full games.|blockhunt.joinfull|blockhunt.moderator|
||Able to join/leave using join/leave signs.|blockhunt.joinsign|blockhunt.player|
||Able to create a join/leave sign.|blockhunt.signcreate|blockhunt.moderator|
||Gives you the BlockChooser.|blockhunt.shop.blockchooser|blockhunt.admin|
||Gives you the ability to do all commands in-game.|blockhunt.allcommands|Operators|

### Other special permissions
|Permission|Description|
|:--|:--|
|`blockhunt.*`|All BlockHunt permissions.|
|`blockhunt.player`|All player related permissions.|
|`blockhunt.moderator`|All moderator related permissions.|
|`blockhunt.admin`|All admin related permissions.|
|`*`|All permissions on your server, including BlockHunt's permissions.|

##
This plugin will be on the license "APACHE 2.0".

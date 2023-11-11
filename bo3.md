# Black Ops 3 Game Tweaks

## 1. config.ini

- disables fps limit
- disables vram limit
- minimizes input latency
- unhides in-game graphics options
- increases graphics quality (past what is possible via in-game setings, even the hidden ones)

**Entering the advanced tab in your graphics options menu will always prompt you to save changes. if you hit save changes (whether or not *you* made any changes), it'll undo some of the config.ini tweaks**

Download [config.ini](https://github.com/bigfinfrank/gametweaks/blob/main/bo3/config.ini) and use it to replace the one at `C:\Program Files (x86)\steamapps\common\Call of Duty Black Ops III\players\config.ini`

## 2. delete loading movies ([steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=557719129))

this will reduce loading times substantially, most of these are the solo-only zombies intro cutscenes (ex. the "hey you~" shadows of evil video)

rename (ex. prefix with `_` or append `.bak`) or delete the following files in `G:\SteamLibrary\steamapps\common\Call of Duty Black Ops III\video`:

- `bo3_global_logo_logosequence.mkv` - game startup intro - deleting this will make the game window entirely black until the main menu loads
- `zm_castle_loadingmovie.mkv` - der eiesendrache
- `zm_factory_load_factoryloadingmovie.mkv` the giant
- `zm_frontend_load.mkv` - zombies forest interstitial loading video - can prevent you from getting stuck
- `zm_genesis_loadingmovie.mkv` revelations
- `zm_island_loadingmovie.mkv` zetsubou no shima
- `zm_prototype_loadingmovie.mkv` nacht der untoten
- `zm_stalingrad_loadingmovie.mkv` gorod krovi
- `zm_theater_fs_loadingmovie.mkv` kino der toten
- `zm_tomb_loadingmovie.mkv` origins
- `zm_zod_load_zodloadingmovie.mkv` shadows of evil

## 3. fast_restart, map_restart & disconnect binds ([steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=1122433143))

fast_restart for quickly restarting maps that aren't super custom, map_restart for restarting (mostly custom maps) that break when using fast_restart, disconnect to keep gobblegums without alt+f4/task manager-ing the game.

replace or add `bind SEMICOLON "disconnect"`, `bind [ "fast_restart"` and `bind ] "map_restart"` to both of the following files:

- `G:\SteamLibrary\steamapps\common\Call of Duty Black Ops III\players\bindings_0.cfg`
- `G:\SteamLibrary\steamapps\common\Call of Duty Black Ops III\players\bindings_1.cfg`

then mark them as read only (right click -> properties -> read-only)

## 4. T7patch (RCE, remote crash, A.B.C error and FPS bug fixes ([steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=2924410249))

"A new and improved community patch for a large list of Black Ops III exploits.", can be found in this repo: https://github.com/shiversoftdev/t7patch.

## 5. missing assets/errors in custom maps that should otherwise be there

1. open your steam library
2. click the search bar
3. type in "black ops iii"
4. install normal black ops iii, the mod tools, remote console, unranked dedicated server
5. (optionally, or if you're still having issues) right click mod tools in the steam library search
6. hit properties
7. go to the dlc tab on the left
8. check the additional assets dlc
9. wait for the 97gb of assets (which your map probably only uses 2mb of) to download

## 6. for streaming / potential exploit mitigation

options -> content filter -> disable both graphic content and user generated content.

options -> chat -> voice -> voice chat volume (NOT voice chat record level) = 0.00

options -> chat -> voice -> uncheck voice chat box

options -> chat -> voice -> check push to talk box

options -> chat -> voice -> turn on mute all except party

options -> controls -> interact -> unbind voice chat

options -> chat -> text -> turn everything off

## 7. mic volume changing every time black ops 3 starts

for some ungodly reason treyarch made the Voice Chat Record level slider change your windows microphone volume.

options -> chat -> adjust voice chat record level to wherever you want it, and never touch this setting again.

## 8. party settings best practices

unless you're *actively* trying to invite someone, keep your (social -> manage party) party privacy set to Closed with player limit set to 1 (or however many people are currently in your party).

when *you are actively* trying to invite someone, bump up your player limit by 1 and set it to friends only.

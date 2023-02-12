# QCDE-Addons

Various add-ons for the outstanding Doom 2 mod QC:Doom Edition by DBThanatos and Michaelis

## LGTrain
LGTrain helps you host a Lightning Gun aim practice server (or use it for offline training) where only two players would fight each other any given time and the rest are waiting in line. After each frag players are healed to the maximum health and armor so that winning is only a matter of aim and movement skills.  
The only allowed class in this game mode is Sarge and there are no healing items spawned.  
When starting a game with this addon loaded, set the following:
```
deathmatch 1          //game mode should be deathmatch, duel won't cut it
rocketarena 6         //Shaft Party
skill 7               //Practice mode, half damage
sv_qcdepowerups 0     //no Quad or Protection
sv_weapondrop false   //no weapon drops
```
If practicing with bots, I also recommend setting the following:
```
botskill 4
bot_twitch 200
```

Happy frying!

[Download 1.25](https://allfearthesentinel.com/zandronum/download.php?file=qcde--lgtrain_v1.27.pk3)  
[Download map pack](https://allfearthesentinel.com/zandronum/download.php?file=qcde--lgtrain-arenas_v1.05.pk3)

## Medals

A continuation of **Ivory Duke**'s QC style [medals add-on](https://www.moddb.com/mods/quake-champions-doom-edition/addons/qcde-medals) updated for QCDE 2.7 with bug fixes, improvements and new medals.
Medals can be turned on/off in the `HUD Options` menu or with the console variable `cl_qcMedals`.  

**NOTE**: This add-on is now included in QC:DE starting from version 3.0, code base will most likely be kept updated here nonetheless. A link to a legacy version can be found below.  

See the included [credits](https://github.com/kultasakaali/QCDE-Addons/blob/main/Medals/!CREDITS!.txt) file for more information and changelog up to the point of integration!  

A list of medals can be found [here](https://github.com/kultasakaali/QCDE-Addons/blob/main/Medals/qcde_medals.pdf).

[Download 1.3 RC5](https://allfearthesentinel.com/zandronum/download.php?file=qcde_medals-qzan_v1.3_rc5.pk3)

## UT Announcer for the Unreal Tournament weapons add-on

An add-on for **geNia**'s [UT Weapons add-on](https://www.moddb.com/mods/quake-champions-doom-edition/addons/unreal-tournament-weapons-for-q-zandronum) that brings multikill and killing spree announcements to the game.  

Currently the pack contains 5 announcers you can choose from via the sound menu or using the `cl_utannouncer` CVar.  

- UT99
- UT2004 Male
- UT2004 Female
- UT2004 Sexy
- UT2003

[Download 1.05](https://allfearthesentinel.com/zandronum/download.php?file=qcde_ut_weapons_announcer_v1.05.pk3)

## RailJump

This add-on will provide you with a Railgun that is able to thrust you in the air, exactly like a rocket jump, with no self-damage. Intended to use with Instagib game mode, however it's not restricted to that.  

**NOTE**: This feature is now provided by QC:DE starting from version 3.0 by the name of RailRecoil. Links to legacy versions can be found below.  

[Download 1.0 for Zandronum](https://allfearthesentinel.com/zandronum/download.php?file=qcde--railjump.pk3)  
[Download 1.3 for Q-Zandronum](https://allfearthesentinel.com/zandronum/download.php?file=qcde--railjump-qzand_v1.3.pk3)

## Server Scripts

- **LMSExtensions**: Loading this add-on will make QC:DE obey the `instagib` and certain `rocketarena` CVars in (T)LMS, thus giving you the tools to host Last Man Standing modes you'd not be able to otherwise. Supported modes include: _instagib, rocket arena, buckshot, unholy trinity, shaft party, random loadout per life_  
**NOTE**: Starting from QC:DE 3.0 loading this add-on is not needed

- **RandomChampion**: This add-on will pick a random champion for each played map/round and force it for every player. Switchable with CVar `sv_randomChampMode` 0: off, 1: per map, 2: per round.  
**NOTE**: This add-on will only work online

- **RandomRocketArena**: Picks a random rocket arena game mode for every new map, switchable on or off with `sv_randomRocketArena`. And yes. Gauntlet and BFG too.

- **RespawnDelay**: A script that will lock you in place for set amount of time after respawning while being invisible and not being able to move, take or inflict damage. `sv_respawnDelay` toggles on or off, `sv_respawnDelayTime` sets the delay timer in seconds. Timer is also randomized by ±20%. Make sure to set the following for the script to have full control on the delay applied to the players:
`sv_forcerespawn true; sv_forcerespawntimer 0`

[Download LMSExtensions 1.01](https://allfearthesentinel.com/zandronum/download.php?file=qcde--lmsextensions_v1.01.pk3)  
[Download RandomChampion 1.26](https://allfearthesentinel.com/zandronum/download.php?file=qcde--randomchampion_v1.26.pk3)  
[Download RandomRocketArena 1.02](https://allfearthesentinel.com/zandronum/download.php?file=qcde--randomrocketarena_v1.02.pk3)  
[Download RespawnDelay 1.0](https://allfearthesentinel.com/zandronum/download.php?file=qcde--respawndelay_v1.0.pk3)

## Stack Left

This simple add-on will display your killer's stack left like in QC. Disabled in duels by default, but can be enabled by the server with `sv_showStackLeftInDuels`. Players who wouldn't like to recieve these messages can turn them off with `cl_showStackLeft`.  
**NOTE**: This feature is now included in QC:DE from version 3.0 onwards

[Download 1.0](https://allfearthesentinel.com/zandronum/download.php?file=qcde--stackleft.pk3)

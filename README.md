# QCDE-Addons

Various add-ons for the outstanding Doom 2 mod QC:Doom Edition by DBThanatos and Michaelis

## LGTrain
LGTrain helps you host a Lightning Gun aim practice server (or use it for offline training) where only two players would fight each other any given time and the rest are waiting in line.
After each frag players are healed to the maximum health and armor so that winning is only a matter of aim and movement skills. The only allowed class in this game mode is Sarge and there are no healing items spawned.
Stats of bots provided by this add-on are maxed out to compensate for online latency. They will not miss a single shot offline.
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

## Medals

A continuation of **Ivory Duke**'s QC style [medals addon](https://www.moddb.com/mods/quake-champions-doom-edition/addons/qcde-medals) updated for QCDE 2.7 with bug fixes, improvements and new medals.
Medals can be turned on/off in the `HUD Options` menu or with the console variable `cl_qcMedals`.

**NOTE**: This addon will only work with Q-Zandronum 1.3, while older testing versions found on TSPG are targeted for Q-Zandronum 1.2.1

See the included credits file for more information and changelog!

## RailJump

This add-on will provide you with a Railgun that is able to thrust you in the air, exactly like a rocket jump, with no self-damage. Intended to use with Instagib game mode, however it's not restricted to that.

## Server Scripts

- **LMSExtensions**: Loading this add-on will make QC:DE obey certain `rocketarena` and the `instagib` CVar, thus giving you the tools to host Last Man Standing modes you'd not be able to otherwise. Supported modes include: _instagib, rocket arena, buckshot, unholy trinity, shaft party, random loadout per life_
- **RandomChampion**: This add-on will pick a random champion for each played map/round and force it for every player. Switchable with CVar `sv_randomChampMode` 0: off, 1: per map, 2: per round
- **RandomRocketArena**: Picks a random rocket arena game mode for every new map, switchable on or off with `sv_randomRocketArena`. And yes. Gauntlet and BFG too.
- **RespawnDelay**: A script that will lock you in place for set amount of time after respawning while being invisible and not being able to move, take or inflict damage. `sv_respawnDelay` toggles on or off, `sv_respawnDelayTime` sets the delay timer in seconds. Timer is also randomized by ±20%.

## Stack Left

This simple add-on will display your killer's stack left like in QC. Disabled in duels by default, but can be enabled by the server with `sv_showStackLeftInDuels`. Players who wouldn't like to recieve these messages can turn them off with `cl_showStackLeft`.

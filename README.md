
# FrostForged Repack

Frostforge was the result of the passion of many authors but originated with Roza. This was a server hosted for people to progress from Classic to WotLK with double 3.3.5a WotLK talents. It featured a bot system that allows the player to accomplish almost all tasks alone and served as a power multiplier for the main character.

This repository at its core is a party-based singleplayer MMORPG repack for World of Warcraft with full blizzlike and custom content for levels 1 through 80 across all zones available during that era of the game. Everything that happened or was changed, including every character and bot created, during the lifetime of the server is included in this package. Most features are adjustable via an easy worldserv.conf file that reads in plain english with examples on how each function works. 
## Features (Modules)

- AutoBalance
- dungeonrespawn
- GainHonorGuard
- instance-reset
- mod_achievements
- mod_ahbot
- mod_boss_announcer
- mod_learnspells
- mod_LuaEngine
- mod_pyptitles
- mod-rdf-expansion
- mod_time_is_time
- npc_beastmaster
- npc_enchanter
- reagent_bank_account
- SkipDKModule
- SoloLfg
- statbooster


## Installation

1. Go to "Releases" then click on "FrostForged-Repack.7z" and download it.
2. Unzip it with your preferred zip program (WinRAR, 7Zip, ...) or with the integrated Windows ZIP Program.
3. Run "MySQL.bat" wait 2-3 seconds (Make sure you if you have MySQL on your computer to disable it from the computer "Services").
4. Run "authserver.exe" wait again 2-3 seconds. The last lines are supposed to be

```bash
Added realm "Frostforge Official" at 0.0.0.10:8085.
Process priority class set to HIGH
```
5. Run "worldserver.exe" The last lines are supposed to be

```bash
AC> Starting up Auction House Listing thread...

AC> Calendar deletion of old events.
```
5. Go to your World of Warcraft installation folder.

6.  Open the Data folder, then the folder for your language (e.g., enUS).

7. Find the file named realmlist.wtf.

8. Right-click it and choose Open with Notepad. (or whatever Text Editor you prefer)

9. Replace all the text with:

```bash
set realmlist 127.0.0.1
```
and Save it to play locally (Solo)
## Support

For support, you can reach out to Hex_TV#2545 or join one of the Discord servers below:


Realms of Azeroth: https://discord.gg/zRw3Qyy8
- ff-repack-support-ff (channel)
  
Hex Tv Community: https://discord.gg/wxgVaz75
- wow-modding-help (channel)

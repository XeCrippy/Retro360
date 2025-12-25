# Create an issue for any bugs found and I will try to fix it. If you're having connection issues then provide as much detailed information as you can. 

*This is just hosting the app download/installer, not the source code

# Retro360 WinUI C++
Xbox 360 RGH/Jtag modding tool. Mainly focused on single player/offline games. 

This project started out just for testing. I was making a c++ version of JRPC.dll (for RTM tools) and testing on a few different UI frameworks. Originally was using Dear ImGui & D3D11 but liked the look and feel of WinUI better. 

Current Features:
* Achievement Manager - Unlock all achievements, unlock individual achievements (optionally with custom timestamp), unlock all avatar awards, unlock all gamer pics
* File Manager - Browse, launch, delete, send, and receive files/directories
* Memory Search - cheat engine style search tool inspired by XeClutch's Xbox 360 Cheat Engine and X360 Trainer Tool
* Leaderboard Hacker - Set leaderboard score to max value for any game
* Some random game mods. Focusing mainly on single player games and games that don't have much available for them.

Info:
* Using WinUI 3 in Visual Studio 2026 Insiders written in C++.
* This is mostly educational, trying to learn more about c++ coming from c#
* This is a work in progress and pretty incomplete at the moment
* Achievement Unlocker should be about finished 

# Achievement Unlocker 
* Pulls achievements data into a listview
* Double click an achievement to unlock
* Works for all games
* Unlock all achievements for any game
* Unlock all avatar awards for any game
* Unlock all gamer pics for any game

# Leaderboard Hacker
* Should work for mos, if not all, games
* Enable from the dashboard or in game
* It will remain hooked until you disable it even when switching games or returning to dashboard
* Sets all stat fields to their max value
* Works for time trial leaderboards as well
* Must get a better score than your previous in order for the leaderboards to update the new stats
* You won't be able to get 1st if someone has already modded theirs to max values.
* From testing, it looks like most of the leaderboards are already ruined anyway. 

Theme responds to system colors
<a href="https://gyazo.com/63ac105a19d255d5d74ef983ee30f838"><img src="https://i.gyazo.com/63ac105a19d255d5d74ef983ee30f838.png" alt="Image from Gyazo" width="1920"/></a>

# Video

[![Retro 360](https://img.youtube.com/vi/bdra5yrOUOw/0.jpg)](https://m.youtube.com/watch?v=bdra5yrOUOw "Retro 360")

# Current games cheats list
XBLA:
* Castle Crashers
* CS:GO
* Doritos Crash Course
* ~~Duke Nukem 3D~~ Not working properly 
* Galaga Legions DX
* Peggle
* Peggle 2

Other Games:
* 007 Legends
* 50 Cent Blood on the Sand
* 50 Cent Blood on the Sand Japan version
* Battlefield Hardline
* Crackdown
* Crackdown 2
* Doom 3 BFG
* Enemy Territory: Quake Wars
* Forza Motorsports 2
* Forza Motorsports 4
* Forza Horizon
* Forza Horizon 2
* GTA San Andreas
* Left 4 Dead 2
* Mortal Kombat 9
* Need For Speed Most Wanted (1st one)
* Resident Evil 6
* Saints Row
* Saints Row 2
* Saints Row The Third
* Saints Row 4
* Saints Row Gat Outta Hell
* Skyrim
* Sleeping Dogs
* Sniper Elite III
* Sniper Ghost Warrior 2
* Sonic & SEGA All Stars Racing
* Sonic & All Stars Racing Transformed
* Sonic The Hedgehog 2006
* Sonic Generations
* Tony Hawk American Wasteland

PC Games:
* FFVII Remake (Latest Steam version)
  
# In progress/Future plans
* Slowly adding call of duty just to be more of a complete all in one tool. I don't have any interest in cod or making anything new for it at the moment so I will add what I already have in other tools.

# Portable Achievement Unlocker Preview 
<a href="https://gyazo.com/3fc6d5e7af37bca7a492f4bfcb8998af"><img src="https://i.gyazo.com/3fc6d5e7af37bca7a492f4bfcb8998af.gif" alt="Image from Gyazo" width="804"/></a>

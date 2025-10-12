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
* Universal Leaderboard editor
  - ~~I have been working on figuring out how people are doing the leaderboard hacks and finally have a working method that should work for most games with leaderboards that are still online. Right now it will hook the function that writes the stats and replace all int32 and int64 values in the stats struct to max or custom values. Will work on other data types next for things like time trials.~~
  - ~~The leaderboard hacker is conplete and will be in the next update. It works well so far. You can enable it from the dashboard or in game and it will remain active when you switch games until you disable it. I haven't ran into any games that it doesn't work for yet.~~
 
* Slowly adding call of duty just to be more of a complete all in one tool. I don't have any interest in cod or making anything new for it at the moment so I will add what I already have in other tools.

*This is just hosting the app download/installer, not the source code

# Retro360 WinUI C++
Xbox 360 RGH/Jtag modding tool. Mainly focused on single player/offline games. 

This project started out just for testing. I was making a c++ version of JRPC and testing on a few different UI frameworks. Originally was using Dear ImGui but liked the look and feel of WinUI better. 

Current Features:
* Achievement Manager - Unlock all achievements, unlock individual achievements (optionally with custom timestamp), unlock all avatar awards, unlock all gamer pics
* File Manager - Browse, launch, send, and receive files/directories
* Memory Search - cheat engine style search tool inspired by XeClutch's Xbox 360 Cheat Engine and X360 Trainer Tool
* Some random game mods. Focusing mainly on single player games and games that haven't already been modded to death

Info:
* Using WinUI 3 in Visual Studio 2022 preview written in C++.
* This is mostly educational, trying to learn more about c++ coming from c#
* This is a work in progress and very incomplete at the moment
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
  - Can currently read stats to retrieve the necessary viewId's, coloumnId's, and propertyId's but have not been able to get the function to call successfully when repopulating the struct and calling the function. Either something in the stuct is incorrect or I'm missing something with creating/capturing the session.
  
  - Can however hook the function and then walk the pointer chain to manually poke the values but that is on a per game basis as of right now.
    
  - My goal is to dump the stats, use the data to repopulate the struct dynamically with the modded values, then either replace the struct or call the function with the correct data. This way it would work for any game with leaderboards.
 
* Slowly adding call of duty just to be more of a complete all in one tool. I don't have any interest in cod or making anything new for it at the moment so I will add what I already have in other tools.

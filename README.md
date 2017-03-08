# DMS-Chernarus-AI-Static-Base
This is a Static AI base for Chernarus running DMS missions. It is heavily armed and is NOT easy. The Base contains M2 Gunners at every entrance, there are also M2 gunners around the inside! the base has three sections, The food/general, Military+Building(Middle), Medical and a random special crate that is spawned somewhere in the mission. The base has 2 roaming Vehicles which are armed these can be Hunter/Ifrit/Offroad.

# Installation Instructions (Thanks to Riker2335 for the instructions!)
1. Copy the AIStaticBase_Chernarus.sqf file to a3_dms.pbo's /missions/static folder
2. Open config.sqf in a3_dms.pbo, find the DMS_StaticMissionTypes section and append ["AIStaticBase_Chernarus",1] to the list
3. Save and close config.sqf
4. re-pack a3_dms.pbo with all the changes and ensure it is placed in the /@ExileServer/Addons folder to launch at server startup.
5. copy the content from InitServer.sqf into your(Important) initserver.sqf file inside your mission file.
6. Repack your mission file and upload to the server

# Optional Install Instructions
These 2 lines provide some preconfigured CUP vehicles and weapons for the mission file if you use those mods on your server.
1. If you have CUP Weapons, uncomment the "#define USE_CUP_WEAPONS 1" line
2. If you have CUP Vehicles, uncomment the "#define USE_CUP_VEHICLES 1" line

http://www.exilemod.com/topic/21734-release-dms-chernarus-static-ai-base-mission/

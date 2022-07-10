IMPROVED GAMEPLAY

Recent Changes: 

   v3.3 balances the chances of fake surrenders and knife suspect counts, as well as tweaks the health of all SWAT operators and suspects for balancing. Updated for and supported for game version "Ready or Not Early Access 21474 (Jun 29 2022)".

Changelog: Improved Gameplay on Github

Gameplay Tips:

Use grenades combined with door breaching to reduce enemy morale, forcing them to surrender.
Watch for traps, check your doors carefully.
Mod favors a more methodical approach to handling suspects. Teamwork helps a lot.

Main Differences from Vanilla:

Health rebalance: Unarmored units will drop fast, especially civilians when hit with high caliber rounds. SWAT and suspects in heavy armor will take more rounds, especially with smaller calibers.
Enemy accuracy and reaction times vary on enemy "skill level" based around the "lore" of a map or layer.
Enemy AI will shoot at breached doors for longer and more accurately based upon the enemy level "skill".
Enemy AI will remember your last known position for much longer, and react accordingly.
C2 breaching charges and grenades are much more effective at reducing enemy morale, and have slightly increased duration.
Beanbags and Pepperballs made slightly more effective.
Door breaching ram made slightly less effective.
Enemies known to use explosives will plant more explosive traps.
"Teen" suspects on Gas will have less accuracy, but will roam and shoot more easily. They only use alarm traps.
Friendly SWAT AI Operator accuracy and response times will vary on layer, but are generally improved over vanilla.
Chances of a random suspect having "God-Tier" accuracy and response times greatly reduced.
Enemy AI will look for cover over greater distances.
Enemy AI will detect SWAT flashlights, gunfire, grenades, and door activity faster and in a more realistic manner.
Enemy AI will remember last detected activity for longer periods of time.
Enemy AI morale can now increase during actions, such as them firing more rounds, increasing their "confidence".
Explosive vests are now only found on the Bomb Threat and Hostage Rescue layers.

Description:

   ﻿A realism and lore focused modification to "AILevelData.ini". Reduces the chances of you and your teammates from getting wiped out while increasing your chances of success so long as you use tactics.
   ﻿Enemy accuracy and response times are reduced, but the number of enemies are increased as well as their changes of roaming. The enemy won't forget your last position nearly as quickly. More trained suspects, such as those encountered during a raid will fire upon breached doors and have quicker reflexes. Every map and layer have been tweaked to be lore friendly (No more grenade traps on Gas with barricaded suspects, it's a robbery gone wrong committed by teens, where the hell did they get flashbangs and bombs from??). Likewise, taking on the group at the farm will be much harder due to them being "trained" and having much better gear, as well as having time to prepare for an eventual SWAT assault after killing the officer out front. Bomb Defusal will have suspects in waiting, and more explosive traps placed throughout a mission.
   ﻿Breaching with C2 will be devastating to enemy morale, and grenades will ensure you have time to breach rooms and get a handle on the environment and contacts before the enemy can respond. Breaching with the ram has been made a bit less effective, but if combined with less-than-lethal grenades it will still be a potent tool.
   ﻿I have included the repacked .pak, as well as the "AILevelData.ini" file with latest changes. I plan on updating the mod and adapting it based on user suggestions, and as game updates release. Please leave comments if you have any suggestions, I try to reply to feedback, even if it is negative, I will take it!

Current Limitations:

Please note that due to the limitations of repacking the game, certain things cannot be changed at this time. This should hopefully change once we have a modding SDK. Things are also sure to change as new versions release, so please be patient with any new versions or workarounds. Such limitations are: Note: Literally everything I wanted to be able to change was made possible by game update 17900 (Jan 29 2022). There are no current limitations.
Cannot change how frequently the suspects will "fake" surrender directly. Increasing enemy morale seems to increase the chances of this happening as a side effect, but this only effects how they behave on first contact, not after you have lowered morale, making them give up easier. This makes enemies almost never "fake" surrender on the knees after a C2 breach and grenade detonation. I decided to make all the gear more realistic and tactical, but this sadly causes less surprises overall at this time. Fixed in game version 17900. NOTE: Values do exist in the .ini and can be changed, but they seem to have no effect! Source: My experience and the "RoN AI Settings" spreadsheet found in the credits.
Some layers (such as "Bomb Threat" on the "Hotel" map) cannot be modified for just that layer without the .pak giving a corrupted file error on load. Only The bomb time can currently be edited. Fixed in game version 17900. This varies from layer to layer and map to map, but in most cases what cannot be changed simply inherits "global" settings.
Cannot change the time a suspect takes to raise a weapon from "rest" position. Currently only able to edit the time they take to "draw" a holstered or hidden weapon. Behavior greatly improved in game version 17900.

Future Plans:

These will only be possible once the game is in a much more completed state, and if/when we get a modkit/mod tools.
Making each map and layer feel unique to the lore. Hopefully can modify and limit weapons the suspects use, as well as their armor types
Properly controlling how fast a suspect can fire on SWAT depending on the situation. Currently can only control how fast they draw if a weapon is holstered, don't have control over how fast they can fire from "rest" position.
Would love to improve friendly AI reports for the Wand and traps. Seems hit or miss at the moment and no control over it.
Some control over spawn points for SWAT and suspects.
Possibly new game modes, like "Terrorist Hunt" (no civilians, limited traps, more engagements and firefights) and "VIP Extraction."
Ability to move suspects and civilians out of danger. (Suspects while cuffed, compliant civilians while both cuffed and uncuffed.)

Credits:

The Ready or Mod﻿﻿﻿ Discord Server
The Ready Or Not Discord Server﻿
kronzky's AIMod﻿﻿
Luigi Auriemma's file extractor and importer QuickBMS
kronzky's RoN AI Settings Google Spreadsheet﻿﻿
The Unofficial Modding Guide by Discord users "QuantumNuke75#3593" and "The Real Sourc3#7480"
Discord user "./beyker[ykt].sh#6699" for asking about a smaller file size, otherwise I never would have guess I could make the mod as small as it is.

Installation via Vortex (Recommended):

1.) Download mod and install with Vortex. Last tested fully working on July 1st , 2022.

Manual Installation:

1. Manually download the mod archive under mail files.
2. Extract the .pak file to "\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks".

Uninstallation:

1. Delete the Improved Gameplay .pak file from "\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks".

Editing:

One can edit the mod by using kronzky's AIMod. This can be done with just that mod, but you can also use my AILevelData.ini listed under archived files, or any other .ini file shared often across the internet. I provide the .pak files for those who don't want to deal with repacking.
If you decided to try on your own, check all the credited sources for more info. They will be of great help as they also helped me.﻿

Notes:

Only the host needs the mod in order for all players while playing online to take effect.
Currently supports "Ready or Not Early Access 21474 (Jun 29 2022)".

Notes for other Modders:

Be aware that some options in AILevelData.ini have little or no effect at all. The Google Spreadsheet listed under Credits notes these in detail.  
Be wary when using QuickBMS. It does a great job of making sure the .pak file is the SAME exact size before and after repacking, but sometimes this is not enough, and you will still end up with a corrupted .pak file. This seems to occur most often when changing values beyond certain unknown set parameters, and even though QuickBMS will give a successful completion with no warning, the .pak file will either not allow Ready Or Not load into the main menu, or it will crash with a corrupted file message when trying to start a session. Make sure you test any changes often!!! (I ran into this issue simply changing a "minflees=-1" into a "0".). Make sure to test any edits you do, especially while the game is still being developed. Many changes can pack correctly but will cause a game error on level loads.
Note: Since game version 17900 (Jan 29 2022) editing the AILevelData.ini has become much easier. The developers not only added many more layers to be editable in the file (as well as the new maps), but they also added tons of comments that explain what values do what. You can delete many of these comments to reduce the file size. This allowed me to make many more edits, as well as add some much needed extra values to other layers without breaking the repack for version 2.0 of the mod.
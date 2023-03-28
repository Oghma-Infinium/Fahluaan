  - [FAQ](#faq)
      - [Q: Should I be worried about the Form 43 Error in MO2?](#q-should-i-be-worried-about-the-form-43-error-in-mo2)
      - [Q: How do I change the bodyslide on my character/on NPCs?](#q-how-do-i-change-the-bodyslide-on-my-characteron-npcs)
      - [Q: I can't level up, what do I do?](#q-i-cant-level-up-what-do-i-do)
      - [Q: How do I get the Static Skill Leveling prompt to show up after leveling up?](#q-how-do-i-get-the-static-skill-leveling-prompt-to-show-up-after-leveling-up)
      - [Q: I leveled up but didn't get any perk points. / How do I get perk points?](#q-i-leveled-up-but-didnt-get-any-perk-points--how-do-i-get-perk-points)
      - [Q: Why can't I damage or kill X Npc?](#q-why-cant-i-damage-or-kill-x-npc)
      - [Q: How do I start the main questline?](#q-how-do-i-start-the-main-questline)
      - [Q: When do dragons start spawning?](#q-when-do-dragons-start-spawning)
      - [Q: Why did the dragon I kill not give me a Dragon Soul?](#q-why-did-the-dragon-i-kill-not-give-me-a-dragon-soul)
      - [Q: How do I become the Thane of Whiterun? How do I get Lydia?](#q-how-do-i-become-the-thane-of-whiterun-how-do-i-get-lydia)
      - [Q: I can't find Altano in the Windpeak Inn. / How do I start VIGILANT?](#q-i-cant-find-altano-in-the-windpeak-inn--how-do-i-start-vigilant)
      - [Q: Why won't Lucien talk to me?](#q-why-wont-lucien-talk-to-me)
      - [Q: I don't like the physics.](#q-i-dont-like-the-physics)
      - [Q: How do I add a Bodyslide to the list?](#q-how-do-i-add-a-bodyslide-to-the-list)
      - [Q: How do I enable my crosshair?](#q-how-do-i-enable-my-crosshair)
      - [Q: How do I get rid of the black bars? How to disable letterbox.](#q-how-do-i-get-rid-of-the-black-bars-how-to-disable-letterbox)
  - [Known Issues](#known-issues)

## FAQ

#### Q: Should I be worried about the Form 43 Error in MO2?  
A: The ["Form 43" warning](https://cdn.discordapp.com/attachments/853785456609329174/1018924398461337731/unknown.png) in the notifications section in the top right of MO2 is completely normal and can be safely ignored. If you want to resave the `.esp`s in the CK to make them be form 44, feel free, it shouldn't break anything.

#### Q: How do I change the bodyslide on my character/on NPCs?  
A: The list uses [AutoBody](https://www.nexusmods.com/skyrimspecialedition/mods/61321) instead of [OBody](https://www.nexusmods.com/skyrimspecialedition/mods/51084) to handle Bodyslide distributions and morphs. By default the keybind to open the AutoBody menu is `;`, but it can be changed in the AutoBody MCM menu.  

#### Q: I can't level up, what do I do?  
A: You likely have SunHelm enabled, go sleep in a bed.

#### Q: How do I get the Static Skill Leveling prompt to show up after leveling up?
A: You need to sleep after leveling up to increase your skills. Unfortunately, making it so the SSL message box popped up after leveling up and leaving menu introduced some unintended bugs, so in order to fix them we had to revert to the original behavior of the mod.

#### Q: I leveled up but didn't get any perk points. / How do I get perk points?
A: Read the [Progression Section](https://github.com/aljoxo/Arisen/blob/main/Documentation/Gameplay%20Guide.md#progression) of the Gameplay Guide. You do not get Perks the traditional way in Arisen.

#### Q: Why can't I damage or kill X Npc?
A: Untick Simple Offence Suppression in the MCM. Tick it back on when you're finished.

#### Q: How do I start the main questline?  
A: If you have chosen to be Dragonborn in the Skyrim Unbound MCM settings, then upon killing your first dragon, you will be summoned by the Greybeards. If you have chosen to not be the Dragonborn, then you can not proceed with the main questline, doing so will also lock you out of a fair amount of content in the list due to the way quest progression is setup.

#### Q: When do dragons start spawning?  
A: By default, dragons are set to be delayed in their spawns from 7 to 21 days after you leave the starting room. By default, dragons will begin showing up at their Word Walls before you will encounter them in the wild.

#### Q: Why did the dragon I kill not give me a Dragon Soul?
A: Was the dragon by Valtheim Towers? Was its name Wuthahrkgolah? This dragon is a friendly NPC from the Citizens of Tamriel mod, and was not designed to be killed by the player. It doesn't give a Dragon Soul.

#### Q: How do I become the Thane of Whiterun? How do I get Lydia?  
A: You must complete [The Blessings of Nature](https://en.uesp.net/wiki/Skyrim:The_Blessings_of_Nature) quest and talk to Jarl Balgruuf when the Gildergreen tree is repaired/the sappling blooms. He'll thank you and allow you to buy the Breezehome, and the standard thaneship quest (help people of the hold and buy a house to become a thane) will be available.

#### Q: I can't find Altano in the Windpeak Inn. / How do I start VIGILANT?  
A: Currently (though this may change in the future), VIGILANT requires the player be level 25, completed House of Horrors, and completed Kindred Judgement (the final quest of Dawnguard DLC). This is because my ideal progression curve for quests should go something like:
   - A guild questline  
   - Main Questline up to A Blade in the Dark  
   - Dawnguard DLC (recommended level: 15-25)  
   - VIGILANT  
   - Main Questline up to at least Alduin's Bane  
   - Dragonborn DLC (minimum level requirement: 40)  
   - GLENMORIL  
   - Main Questline through Dragonslayer (if not previously completed)  
   - UNSLAAD  
Please note that there are other quest mods in the list, aswell as a lot of other content, so they should be filled in wherever to gain levels and experience. This is just a rough map of my ideal character and power progression.  

#### Q: Why won't Lucien talk to me?
A: You selected They/Them pronouns. Go into the Pronouns MCM, select She/Her or He/Him, then speak to Lucien again. After you have gotten him as a follower, you are free to switch back to They/Them.

#### Q: I don't like the physics.  
A: This isn't a question. If you don't like the body physics preset included in the list, I suggest disabling `3BA RFBBBT v3.0 - AutoGibbon Settings - Update 3` in MO2 (if you want a more "stiff" preset) or searching nexus for a new CBPC preset that is more "jello-like".  

#### Q: How do I add a bodyslide to the list?
A: You have two ways to go about this. The way I would suggest is to open the following file `[Path to Modlist]\mods\AutoBody AE - Configurable Randomized Bodies\autoBody\Config\morphs.ini` and add the bodyslide's `.xml` name to the end of the `All|Female|(InsertRace)=` line. Alternatively, if you do hate the way bodyslide presets are distributed in the list, you can either delete the entire `morphs.ini` file or (more reasonably) delete all of the lines in the file that are `All|Female|(InsertRace)`. Please note that you **do not** need to build the bodyslide preset in Bodyslie as all armors are already built and Zeroed Sliders to support AutoBody (which functions like OBody).

#### Q: How do I enable my crosshair?
A: Disable the `Contextual Crosshair` mod, under the "Heads Up Display (HUD)" Separator in MO2.

#### Q: How do I get rid of the black bars? How to disable letterbox.
A: Open the ENB Menu (Default `Shift+Enter`), Open `ENBPOSTPASS.FX`, Scroll down until you see "letterbox" and untick it, Press the "Save Configuration" button, Close the ENB Menu.

## Known Issues

#### Being randomly attacked or arrested by NPCs!
Solution(s)
 1. open the console, select one of the NPCs, and type `paycrimegold 0 0`

#### Tolfdir won't initiate dialogue with Ancano during the "The Eye of Magnus" quest!
Solution(s)
 1. Once in the Hall of the Elements, after Ancano finishes talking, click on Tolfdir in console and type `disable` followed by `enable`. This should trigger the fight to start.

#### The frozen enemies in Auriel's Chapel are in the ceiling during "Touching The Sky" quest!
Solution(s)
 1. Open the Precision MCM, select 'Debug', and set a toggle key. Toggle Precision off before entering Auriel's Chapel, and turn it back on when all the frozen enemies are dead. 
 2. You can use TCL and kill commands with scroll wheel to kill them one by one.
   - Note: If you use the `killall` command, Arch-Curate Vyrthur will die when reaching him. This can break his scripted dialogue scene with Serana, thereby completely breaking the quest. It is highly suggested that you do not use the `killall` command.

#### Alduin's Bane Cutscene Stuck! / Alduin not landing during Elder Scroll Cutscene!
Solution(s)
 1. Open console and type `setstage mq206 32` to make Alduin land on the word wall.
 2. If this still doesn't fix the scene, type `setstage mq206 70` to learn the Dragonrend Shout.
 3. If Alduin seems to be infinitely fighting with the NPCs, type `setstage mq206 100` to finish the cutscene and return to Throat of the World. (Note: Do not use this step as your first resort.)

#### Black Screen when getting on Odahviing to travel to Skuldafn!
Solution(s)
 1. Deactivate Precision and Precision Creatures and rerun Nemesis (it is safe to re-enable these once you are in Skuldafn).
 2. When mounting Odahviing to travel to Skuldafn, once he takes off the ground, open console and type `coc SkuldafnStart`. As long as the next stage of the quest is marked this should cause no bugs and let you continue the quest as normal.

#### Black Screen when entering Waking Dreams after the "The Gardener of Men" quest!
Solution(s)
 1. Deactivate Precision and Precision Creatures and rerun Nemesis. After riding the Dragon up to Miraak's platform, it should be safe to re-enable these.

#### [Insert Issue with the Civil War]
Solution(s)
 1. The civil war is broken in vanilla. I generally suggest not doing it.
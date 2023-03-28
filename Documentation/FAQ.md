![](https://raw.githubusercontent.com/aljoxo/Fahluaan/main/images/Banner.webp)

<p align="center">
  [ <a href="https://github.com/aljoxo/Fahluaan/blob/main/README.md">Installation</a> |
  <a href="https://github.com/aljoxo/Fahluaan/blob/main/GAMEPLAY.md">Gameplay Guide</a> |
  <a href="https://github.com/aljoxo/Fahluaan/blob/main/CHANGELOG.md">Changelog</a> |
  <a href="LINK">Full Modlist</a> |
  <a href="https://github.com/aljoxo/Fahluaan/blob/main/Documentation/FAQ.md">FAQ</a> |
  <a href="https://ko-fi.com/aljoxo">Ko-fi</a> ]
</p>

---

# FAQ

## Q: How do I change the bodyslide on my character/on NPCs?  
A: The list uses [AutoBody](https://www.nexusmods.com/skyrimspecialedition/mods/61321) instead of [OBody](https://www.nexusmods.com/skyrimspecialedition/mods/51084) to handle Bodyslide distributions and morphs. By default the keybind to open the AutoBody menu is `;`, but it can be changed in the AutoBody MCM menu.  

## Q: I can't level up, what do I do?  
A: You likely have SunHelm enabled, go sleep in a bed.

## Q: How do I get the Static Skill Leveling prompt to show up after leveling up?
A: You need to sleep after leveling up to increase your skills. Unfortunately, making it so the SSL message box popped up after leveling up and leaving menu introduced some unintended bugs, so in order to fix them we had to revert to the original behavior of the mod.

## Q: I leveled up but didn't get any perk points. / How do I get perk points?
A: Read the [Progression Section](https://github.com/aljoxo/Arisen/blob/main/Documentation/Gameplay%20Guide.md#progression) of the Gameplay Guide. You do not get Perks the traditional way in Arisen.

## Q: Why can't I damage or kill X Npc?
A: Untick Simple Offence Suppression in the MCM. Tick it back on when you're finished.

## Q: How do I start the main questline?  
A: If you have chosen to be Dragonborn in the Skyrim Unbound MCM settings, then upon killing your first dragon, you will be summoned by the Greybeards. If you have chosen to not be the Dragonborn, then you can not proceed with the main questline, doing so will also lock you out of a fair amount of content in the list due to the way quest progression is setup.

## Q: When do dragons start spawning?  
A: By default, dragons are set to be delayed in their spawns from 7 to 21 days after you leave the starting room. By default, dragons will begin showing up at their Word Walls before you will encounter them in the wild.

## Q: Why did the dragon I kill not give me a Dragon Soul?
A: Was the dragon by Valtheim Towers? Was its name Wuthahrkgolah? This dragon is a friendly NPC from the Citizens of Tamriel mod, and was not designed to be killed by the player. It doesn't give a Dragon Soul.

## Q: How do I become the Thane of Whiterun? How do I get Lydia?  
A: You must complete [The Blessings of Nature](https://en.uesp.net/wiki/Skyrim:The_Blessings_of_Nature) quest and talk to Jarl Balgruuf when the Gildergreen tree is repaired/the sappling blooms. He'll thank you and allow you to buy the Breezehome, and the standard thaneship quest (help people of the hold and buy a house to become a thane) will be available.

## Q: I can't find Altano in the Windpeak Inn. / How do I start VIGILANT?  
A: Currently (though this may change in the future), VIGILANT requires the player be level 25, completed House of Horrors, and completed Kindred Judgement (the final quest of Dawnguard DLC). Similarly, GLENMORIL and UNSLAAD require certain quests to be completed in order to be played. GLENMORIL requires Vigilant, At the Summit of Apocrypha (the final quest of the Dragonborn DLC), and Sacred Anatomancer (a quest from Vigilant that can be started in the Ratway) to be completed. UNSLAAD requires the completion of GLENMORIL and Dragonslayer (the final quest of the Main Questline).

## Q: Why won't Lucien talk to me?
A: You selected They/Them pronouns. Go into the Pronouns MCM, select She/Her or He/Him, then speak to Lucien again. After you have gotten him as a follower, you are free to switch back to They/Them.

## Q: I don't like the physics.  
A: This isn't a question. If you don't like the body physics preset included in the list, I suggest disabling `3BA RFBBBT v3.0 - AutoGibbon Settings - Update 3` in MO2 (if you want a more "stiff" preset) or searching nexus for a new CBPC preset that is more "jello-like".  

## Q: How do I get rid of the black bars? How to disable letterbox.
A: Open the ENB Menu (Default `Shift+Enter`), Open `ENBPOSTPASS.FX`, Scroll down until you see "letterbox" and untick it, Press the "Save Configuration" button, Close the ENB Menu.

# Known Issues

## Being randomly attacked or arrested by NPCs!
Solution(s)
 1. open the console, select one of the NPCs, and type `paycrimegold 0 0`

## Tolfdir won't initiate dialogue with Ancano during the "The Eye of Magnus" quest!
Solution(s)
 1. Once in the Hall of the Elements, after Ancano finishes talking, click on Tolfdir in console and type `disable` followed by `enable`. This should trigger the fight to start.

## [Insert Issue with the Civil War]
Solution(s)
 1. The civil war is broken in vanilla. I generally suggest not doing it.
![](https://raw.githubusercontent.com/Oghma-Infinium/Fahluaan/main/images/Banner.webp)

<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/87820">Nexus</a> |
  <a href="https://github.com/Oghma-Infinium/Fahluaan/blob/main/README.md">Installation</a> |
  <a href="https://github.com/Oghma-Infinium/Fahluaan/blob/main/GAMEPLAY.md">Gameplay Guide</a> |
  <a href="https://github.com/Oghma-Infinium/Fahluaan/blob/main/CHANGELOG.md">Changelog</a> |
  <a href="https://loadorderlibrary.com/lists/fahluaan">Modlist</a> |
  <a href="https://github.com/Oghma-Infinium/Fahluaan/blob/main/Documentation/FAQ.md">FAQ</a> |
  <a href="https://github.com/Oghma-Infinium/Fahluaan/blob/main/Documentation/CONFIG.md">Configuration</a> |
  <a href="https://github.com/Oghma-Infinium/Fahluaan/blob/main/ADDONS.md">Addons</a> |
  <a href="https://ko-fi.com/aljoxo">Ko-fi</a> | 
  <a href="https://www.patreon.com/aljoxo">Patreon</a> ]
</p>

---

## Optional Addons

The following sections detail the **supported** modifications to the list. Any other modifications should be discussed in the `#fahluaan-modifications` channel of the [Waking Dreams](https://discord.gg/4WwqfK5yHg) support server.

### Performance Options

This section will cover the `Performance Options` section of the modlist. Due to Fahluaan's relatively good performance, at least in the data that has been collected, the performance options are not extremely robust to keep users from having to download additional LOD Outputs.

Currently the only supported performance modifications include some Performance-oriented ENB and Grass tweaks, which should provide a 20-40% net performance gain, depending on hardware and area, with minimal loss in the visual fidelity of the list. In order to use these Performance tweaks, activate the `Performance Mode` mod under the `Performance Options` separator in MO2 and disable the following mods above it:
 - `Cathedral - 3D Pine Grass for ENB Complex Grass`
 - `Origins of forest for ENB Complex Grass`
 - `Folkvangr for ENB Complex Grass`
 - `QW Grass 2 for ENB Complex Grass Patch`

### Insects Begone

For those with arachnophobia and/or entomophobia, the `Insects Begone` Separator contains some mods to remove most of the spider and insect adjacent models and enemies from the list. Some aspects of the list's vision are compromised to support these tweaks.

### Optional Tweaks

This section will cover the following Optional Tweaks that are included as a part of the modlist. Please note that if you do any of these tweaks, it is in your best interest to share this information when reporting any potential bugs that you encounter when playing the modlist.
 1. **Yet Another Music Merge - Content Creator Version**: Read more [here](#note-for-content-creators).
 2. **Content Creator Music Patches**: Read more [here](#note-for-content-creators).
 3. **Blade and Blunt - Vanilla Difficult Modifiers**: Restores Vanilla Difficulty Multipliers for those who want an easier experience.
 4. **QuickLoot RE - Disable in Combat**: An edited `.toml` file for QuickLoot RE to disable the loot box from appearing while in combat.
 5. **No ENB Lens Effect**: Disables ENB Lens effect (the frost and rain overlays).
 6. **No Survival Camera Effects**: Removes the image space effects added by CC Survival Mode.
 7. **Vigilant - No Enemy Blur**: Removes the image space blur effects that some enemies produce in Act 3 of Vigilant.
 8. **Lux - Brighter Templates**: Overwrites Lux's base lighting templates with brighter ones, for those who find interiors to be too dark.
 9. **V's Blursed RaceMenu Presets**: Brings back some classic meme presets seen in older versions of the list. Optional to enable.
 10. **NeverNude**: (Enabled by default), Removes Female nudity from the list, the list does not support male nudity without modifications.
 11. **Khajiit Speak Patch**: Patches all Dialogue in the list to act like [Khajiit Speak](https://www.nexusmods.com/skyrimspecialedition/mods/441).
 12. **ENB Dynamic Cubemaps**: Enable if using Dynamic Cubemap setting in ENB.
 13. **Journeyman - A Fast Travel Overhaul**: Redesigns fast travel, read the [modpage](https://www.nexusmods.com/skyrimspecialedition/mods/92220) for more info.

## Changing Keybinds

This section is going to be short and basic and only cover keybinds that must be changed OUT OF GAME, I trust that you will be able to figure out the other keybinds swaps in game. Please refer the [this](https://www.creationkit.com/index.php?title=Input_Script#DXScanCodes) page for the DXScanCodes used by most mods.

1. **Dual Wield Blocking**: Open the mod `Dual Wield Parrying - Settings` and locate the `DualWieldParryingSKSE.ini` file.
2. **Dodging**: Open the mod `TK Dodge - Settings` and locate the `TK Dodge RE.ini` file.

## Changing Resolution

By default, Wabbajack will set the resolution in your `Skyrimprefs.ini` to match the native resolution of your monitor. However, Skyrim scales very poorly at resolutions above 1080p (`1920x1080`) and depending on your hardware, it might be difficult to achieve consistent FPS on higher resolutions.

The preferable way to change your resolution is to find the `SSEDisplayTweaks.ini` located in the `SSE Display Tweaks` mod. Open the file and navigate to the `[Render]` section and find the lines `#Resolution=1920x1080` and `#ResolutionScale=0.75`. Here you can change the resolution here to your desired resolution. After changing the resolution, remove the `#` in order for the settings to take affect when launching the game.

Example for how the .ini line should look:
Before: `#Resolution=1920x1080`  
After: `Resolution=2560x1440`

## Skyrim Upscaler

While [Skyrim Upscaler](https://www.nexusmods.com/skyrimspecialedition/mods/80343) is an unsupported addition, it is asked about often enough that I felt I should put this here. In order to make sure your Upscaler works, you must change some lines in the `SSEDisplayTweaks.ini`. 

In the `SSEDisplayTweaks.ini` make sure that `Fullscreen = false`, `Borderless = true`, and `BorderlessUpscale = false` under the `[Render]` section.

## In-Game MCM options

Most MCMs will come pre-configured, the following is a list of Mod Configuration Menus that I have deemed may be beneficial to play around with as a user.
 - **Skyrim Unbound**: Choose your Standing Stone, starting location, starting equipment, starting wealth, etc. By default, the player is set to become Dragonborn, so if you do not want that for some reason, turn it off. **I highly suggest against choosing to not become Dragonborn, as it will lock you out of a lot of content within the list.**
 - **Improved Alternate Conversation Camera**: Edit the dialogue view. Can also be done through the `.ini` file in Mod Organizer.
 - **OBody Standalone**: Set OBody menu key here. (Default: `;`).
 - **Skyrim Outfit System**: This mod can be used to essentially acheive armor [transmogrification](https://www.merriam-webster.com/dictionary/transmogrify) in Skyrim, read more on the usage on the [modpage](https://www.nexusmods.com/skyrimspecialedition/mods/42162).
 - **SmoothCam**: Default preset is a slightly modified version of Vanilla Enhanced 2.0.
 - **Ultimate Immersion Toggle**: Hide UI Keybind. (Default: `X`).
 - **Weapon Styles**: If you change where your weapon sheathes via IED, then change the animation here so it matches correctly.

## Wheeler

I am only writing this section because it is commonly asked enough that I feel I need to write it down on the list's documentation to have an easy place to point people. Almost this entire section is copy-pasted from the [Wheeler mod page](https://www.nexusmods.com/skyrimspecialedition/mods/97345).

### Wheel Editing

Changes to the wheel can be made when you open the wheel in either the inventory or magic menu. When you open the wheel in these two menus, the background will grey out, suggesting that you're now in **edit mode**.

#### Creation

By default, create an empty wheel using the "N" key and an empty slot using the "M" key. You can create as many wheels and as many slots in a single wheel as you'd like.

#### Insertion

To insert an item or magic into the slot, hover on the item you desire in the inventory, open the wheel, and left-click (right shoulder) on the entry you wish to insert the item into.

#### Ordering

To change a slot's order in a wheel, press the up/down arrow to swap its position with neighboring slots.

To change a wheel's ordering among all wheels, press the left/right arrow to swap its position with neighboring wheels.

#### Deletion

To delete an item from a slot, simply right-click on the item you wish to delete.

Right-clicking on an empty slot deletes the slot.

Right-clicking on an empty wheel deletes the wheel (you can't delete the last wheel).
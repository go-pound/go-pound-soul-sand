# Changelog

If you commit changes, please add release notes here!

## Upcoming

* Disabled Inventory Profiles' inventory scrolling in favor of Mouse Tweaks' positionally-aware scrolling feature. If you already have the mod pack installed, these changes may not be picked up automatically. To set them yourself:
  * Go to Mods > Inventory Profiles Next > Configure > Hotkeys, and clear the default "Scroll Wheel Up" and "Scroll Wheel Down" bindings for "Scroll Items from Player to Chest" and "Scroll Items from Chest to Player" by clicking on each hotkey button and pressing <kbd>esc</kbd>.
  * Go to Mods > Mouse Tweaks > Configure, and set "Scroll Direction" to "Inventory Position Aware".

**Full changelog**: https://github.com/go-pound/go-pound-soul-sand/compare/v1.0.2+1.19.2...main

## 1.0.2+1.19.2

* Bumped Supplementaries to [2.2.27](https://www.curseforge.com/minecraft/mc-mods/supplementaries/files/4172002).
* Bumped Ecologics to [2.1.11](https://www.curseforge.com/minecraft/mc-mods/ecologics/files/4171284).
* Bumped Moonlight Lib to [2.1.19](https://www.curseforge.com/minecraft/mc-mods/selene/files/4174745).
* Bumped Xaero's World Map to [1.28.6](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map/files/4181119).
* Bumped Xaero's Minimap to [22.17.0](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap/files/4181107).
* Bumped Open Parties and Claims to [0.16.5](https://www.curseforge.com/minecraft/mc-mods/open-parties-and-claims/files/4159960).
* Bumped Inventory Profiles Next to [1.9.0](https://modrinth.com/mod/inventory-profiles-next/version/fabric-1.19.2-1.9.0).
* Bumped libIPN to [2.0.0](https://modrinth.com/mod/libipn/version/fabric-1.19.2-2.0.0).
* Bumped EMI to [0.5.2](https://modrinth.com/mod/emi/version/e8yMWd29).
* Replace JourneyMap default key bindings with Xaero's Minimap and World Map bindings.
* Resolve conflicts in the default key bindings:
  * Gameplay > [Tom's Simple Storage] Open Terminal is <kbd>shift</kbd> + <kbd>t</kbd> to avoid conflicting with Multiplayer > Open Chat (<kbd>t</kbd>)
  * TrashSlot > Delete All Items of Type is <kbd>shift</kbd> + <kbd>delete</kbd>
  * TrashSlot > Show/Hide TrashSlot is <kbd>alt</kbd> + <kbd>t</kbd> to avoid conflicting with Multiplayer > Open Chat (<kbd>t</kbd>)
  * Traveler's Backpack > Swap Tool or Change Hose Mode is <kbd>shift</kbd> + <kbd>z</kbd> to avoid conflicting with Xaero's Minimap > Enlarge Minimap (<kbd>z</kbd>)
  * Xaero's Minimap > New Waypoint is <kbd>shift</kbd> + <kbd>b</kbd> to avoid conflicting with Traveler's Backpack > Backpack Inventory (<kbd>b</kbd>)
* Added [Easy Emerald Tools](https://www.curseforge.com/minecraft/mc-mods/simple-emerald-tools-fabric) 1.4.38.
* Added [Freecam](https://www.curseforge.com/minecraft/mc-mods/free-cam) 1.1.6. Use <kbd>F4</kbd> to toggle the free camera.
* Enabled Traveler's Backpack Curios integration. Equip a backpack by hovering over your chest armor slot to make Curios' backpack slot appear.
* Tweak Inventory Profiles Next defaults to disable its sorting buttons when viewing a Traveler's Backpack inventory (the backpack has its own sorting buttons), allow picked-up items to use hotbar slots as in vanilla Minecraft, and allow unenchanted tools under 500 durability to break (so unenchanted wood, stone and iron picks will be used up as usual, but any enchanted or high-tier tools will be saved from accidental destruction). If you already have the mod pack installed, the latter two changes won't be picked up automatically. To set them yourself, go to Mods > Inventory Profiles Next > Configure, and set:
  * Locked Slots > Pick Items Directly into the Inventory to **false**
  * Auto Refill > Allow Some Non Enchanted Gear to Break to **true**

**Full changelog**: https://github.com/go-pound/go-pound-soul-sand/compare/v1.0.1+1.19.2...v1.0.2+1.19.2

## 1.0.1+1.19.2

* Added [Decorative Blocks](https://www.curseforge.com/minecraft/mc-mods/decorative-blocks) 3.0.0.
* Bumped Iris to [1.4.5](https://modrinth.com/mod/iris/version/1.19.2-v1.4.5).
* Bumped Tom's Simple Storage to [1.4.5](https://modrinth.com/mod/toms-storage/version/1.19-1.4.5-fabric).
* Bumped Lithium to [0.10.4](https://modrinth.com/mod/lithium/version/7scJ9RTg).
* Added [Advanced Tooltips](https://modrinth.com/mod/advanced-tooltips) 1.6.0.

**Full changelog**: https://github.com/go-pound/go-pound-soul-sand/compare/v1.0.0+1.19.2...v1.0.1+1.19.2

## 1.0.0+1.19.2 ???????

* Added [AutoRun](https://modrinth.com/mod/autorun) 0.5.0.
* Bumped Iris to [1.4.3](https://modrinth.com/mod/iris/version/1.19.2-v1.4.3).
* Bumped Create to [0.5.0g](https://modrinth.com/mod/create-fabric/version/ZOucvJwc).
* Bumped William Wythers' Overhauled Overworld to [3.1.9](https://www.curseforge.com/minecraft/mc-mods/william-wythers-overhauled-overworld/files/4127867).
* Added the companion resource pack for [TrixyBlox' Ultimate Survival World](https://www.youtube.com/watch?v=dd0GmPyWKV4).
* Added a Docker Compose file that starts a Minecraft server for easy local development. See "Setting up a local development environment" in README.md.
* Increased biome size by tweaking William Wythers' Overhauled Overworld and TerraBlender configuration.
* Disabled mod update notifications for Immersive Portals, Iris, and Xaero's Minimap and World Map by default.
* Bumped Xaero's Minimap to [22.16.3](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap/files/4127323).
* Bumped Xaero's World Map to [1.28.4](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map/files/4127339).
* Bumped Traveler's Backpack to [8.2.8](https://www.curseforge.com/minecraft/mc-mods/travelers-backpack-fabric/files/4134128).
* Disabled BCLib's mod and config synchronization.
* Bumped EMI to [0.5.0](https://modrinth.com/mod/emi/version/p9jbOqyn).
* Bumped Fastload to [2.4.4](https://modrinth.com/mod/fastload/version/mBNst1pT).
* Bumped ImmediatelyFast to [1.0.5](https://modrinth.com/mod/immediatelyfast/version/Lj7lpgeu).
* Bumped Farmer's Delight to [1.3.9](https://modrinth.com/mod/farmers-delight-fabric/version/baQ9tohQ).
* Disabled EMI's "append mod ID to item tooltips" option by default, because another mod already does that, and it was resulting in duplicate mod names in every tooltip. If you already have the mod pack installed, this won't be changed for you???you'll need to open EMI's settings in-game and turn it off in the "UI" section.
* Bumped Traveler's Backpack to [8.2.9](https://www.curseforge.com/minecraft/mc-mods/travelers-backpack-fabric/files/4139514).
* Added [Light Overlay](https://modrinth.com/mod/light-overlay) 7.0.0.
* Added [Quick Connect Button](https://modrinth.com/mod/quickconnectbutton) 1.2.1. There's now a "Pound It!" button on the main menu that will connect you directly to `minecraft.gopound.party`!

**Full changelog**: https://github.com/go-pound/go-pound-soul-sand/compare/v1.0.0-pre5+1.19.2...v1.0.0+1.19.2

## 1.0.0-pre5+1.19.2

* Added [Time & Wind](https://www.curseforge.com/minecraft/mc-mods/time-wind) 1.4.3.
* Added [LambDynamicLights](https://modrinth.com/mod/lambdynamiclights) 2.1.2.

**Full changelog**: https://github.com/go-pound/go-pound-soul-sand/compare/v1.0.0-pre4+1.19.2...v1.0.0-pre5+1.19.2

### Compatibility

* Minecraft 1.19.2
* Fabric 0.14.10

## 1.0.0-pre4+1.19.2

* Bumped BCLib to [2.1.3](https://modrinth.com/mod/bclib/version/2.1.3) to fix compatibility with Better Nether 7.1.2.
* Bumped Moonlight Lib to [2.1.10](https://www.curseforge.com/minecraft/mc-mods/selene/files/4096608) to fix compatibility with Supplementaries 2.2.21.

**Full changelog**: https://github.com/go-pound/go-pound-soul-sand/compare/v1.0.0-pre3+1.19.2...v1.0.0-pre4+1.19.2

### Compatibility

* Minecraft 1.19.2
* Fabric 0.14.10

## 1.0.0-pre3+1.19.2

* Bumped Inventory Profiles Next to [1.8.5](https://modrinth.com/mod/inventory-profiles-next/version/fabric-1.19.2-1.8.5).
* Bumped Iris to [1.4.2](https://modrinth.com/mod/iris/version/1.19.x-v1.4.2).
* Bumped Debugify to [2.8.0](https://modrinth.com/mod/debugify/version/2.8.0).
* Bumped Enhanced Block Entities to [0.7.2](https://modrinth.com/mod/ebe/version/0.7.2+1.19.2).
* Bumped Fastload to [2.3.5](https://modrinth.com/mod/fastload/version/1.19.2.fabric.1.3.5). (The Modrinth release is erroneously labeled as 1.3.5.)
* Bumped ImmediatelyFast to [1.0.4](https://modrinth.com/mod/immediatelyfast/version/1.0.4).
* Bumped Lithium to [0.10.2](https://modrinth.com/mod/lithium/version/mc1.19.2-0.10.2).
* Bumped EMI to [0.4.2](https://modrinth.com/mod/emi/version/0.4.2+1.19).
* Bumped Universal Graves to [2.1.3](https://modrinth.com/mod/universal-graves/version/2.1.3+1.19.2).
* Bumped WTHIT to [5.13.4](https://modrinth.com/mod/wthit/version/fabric-5.13.4).
* Bumped Auditory to [0.0.4](https://modrinth.com/mod/auditory/version/0.0.4).
* Bumped Better Nether to [7.1.2](https://modrinth.com/mod/betternether/version/7.1.2).
* Bumped Connectible Chains to [2.1.4](https://modrinth.com/mod/connectible_chains/version/v2.1.4+1.19.2).
* Bumped Dynamic Surroundings to [0.1.1](https://modrinth.com/mod/dynamicsurroundings_remasteredfabric/version/0.1.1).
* Bumped Farmer's Delight to [1.3.6](https://modrinth.com/mod/farmers-delight-fabric/version/1.3.6).
* Bumped Immersive Portals to [2.3.1](https://modrinth.com/mod/immersiveportals/version/2.3.1-1.19.2).
* Bumped Supplementaries to [2.2.21](https://www.curseforge.com/minecraft/mc-mods/supplementaries/files/4100718).
* Bumped Towns and Towers to [1.10](https://modrinth.com/mod/towns-and-towers/version/1.10-FABRIC).
* Bumped Traveler's Backpack to [8.2.7](https://www.curseforge.com/minecraft/mc-mods/travelers-backpack-fabric/files/4081454).

**Full changelog**: https://github.com/go-pound/go-pound-soul-sand/compare/v1.0.0-pre2+1.19.2...1.0.0-pre3+1.19.2

### Compatibility

* Minecraft 1.19.2
* Fabric 0.14.10

## 1.0.0-pre2+1.19.2

Create Fabric for Minecraft 1.19 is finally here!

* Added Create Fabric [0.5.0f](https://modrinth.com/mod/create-fabric/version/1.19.2-0.5.0f-776).
* Bumped Fabric Loader to [0.14.10](https://github.com/FabricMC/fabric-loader/releases/tag/0.14.10).
* Bumped Fabric API to [0.67.0+1.19.2](https://modrinth.com/mod/fabric-api/version/0.67.0+1.19.2).
* Bumped Xaero's World Map to [1.28.3](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map/files/4075427).
* Bumped Xaero's Minimap to [22.16.2](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap/files/4075402).
* Hide Inventory Profiles Next's GUI configuration button by default. It can be re-enabled in the mod's settings.

**Full changelog**: https://github.com/go-pound/go-pound-soul-sand/compare/v1.0.0-pre1+1.19.2...v1.0.0-pre2+1.19.2

### Compatibility

* Minecraft 1.19.2
* Fabric 0.14.10

## 1.0.0-pre1+1.19.2

Added the initial set of mods and configuration. We're still waiting on a Minecraft 1.19-compatible release of Create Fabric.

### Compatibility

* Minecraft 1.19.2
* Fabric 0.14.9

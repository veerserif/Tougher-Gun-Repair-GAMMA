# Tougher-Gun-Repair-GAMMA
 Makes gun repair more difficult. Designed for GAMMA 0.9.3

## Goals
- Keep GAMMA 0.9.3's "no overall gun condition" idea
- Keep the focus on repair kits and cleaning kits as the key items for fixing weapons
- Make part swapping (as in, fixing parts outside of the gun, then replacing the parts via field strip/workbench) a viable alternative to repairing parts inside the guns ("in-gun repair")
- Make repair kits and cleaning kits more difficult to obtain
- Make gun repair a longer process that requires more inputs (in the form of crafting items or money) to fix a gun

## What does this mod do?

This mod is designed to make gun repair more challenging, requiring more money and materials to fix. It also lowers the condition of barrels that you'll find. Some of these settings can be configured in this mod's Mod Config Menu settings - read the tooltips to figure out what they do. Other settings can be altered in `scripts/tougher_gun_repair_config.script`.

### Cleaning kits and repair kits
- Cleaning kits now **only add +15%** to parts, and can only be used if the part is over a configurable threshold (60% by default)
- Repair kits now **only add +20%** to parts, and can only be used on parts from 0 - 60%
  - If you use the repair kit to clean a gun part, **outside of a workbench**, it **caps condition gain to 60%**
- Using a repair kit charge to clean a gun part (as in, right click the gun ==> "Replace part") will always add half of the repair threshold, rounded up (+30% by default)

### Workbenches
- Cleaning kits and repair kits gain a +5% bonus if you use them at a workbench to clean gun parts (as in, cleaning kits will add + 20% and repair kits will add +25%)
- Barrels can only be replaced at an **actual workbench**, not if you just double-click or Use a set of tools out in the field

### Other changes
- Weapons **never spawn** with a usable barrel. ALL guns require some level of maintenance in order to get them fully working.
- Hidden gun condition is now locked to 95% - this should mean that your guns jam far less frequently once fully fixed, and hopefully sidesteps issues with Nimble or other gun trade quests
- 

## How to install
- Download the mod from the **releases** tab. Do not extract.
- Install it with Mod Organizer 2:
  - In Mod Organizer 2, go to File -> Install mod...
  - Select this mod
  - Click "OK" on the install popup. The mod should appear at the end of your modlist.
  - Enable the mod.

(Include notes on load order and compatibility here)

### Release notes

(Link to the Releases tab here)

- Test release: "bare minimum" version for testing.

## Credits

This is a collaboration between Serious and Veer. By which I mean one of us wrote nearly all of the mod while the other one made appreciative clapping noises.

- Veerserif's other mods: [find them on Discord](https://discord.com/channels/912320241713958912/1257380080397844533/1257390905560928297)
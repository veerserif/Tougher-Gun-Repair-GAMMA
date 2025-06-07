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
- Repair kits now **only add +20%** to parts, and can only be used on parts from 1 - 60%
  - This means you can't use a repair kit to replace missing parts any more - you must find a part from somewhere, first
  - If you use the repair kit to clean a gun part, **outside of a workbench**, it **caps condition gain to 60%**
- Using a repair kit charge to clean a gun part (as in, right click the gun → "Repair part") will always add half of the repair threshold, rounded up (+30% by default)

### Workbenches
- Cleaning kits and repair kits gain a +10% bonus if you use them at a workbench to clean gun parts (as in, cleaning kits will add +25% and repair kits will add +30%)
- Barrels can only be replaced at an **actual workbench**, not if you just double-click or Use a set of tools out in the field

### Other changes
- Initially, no weapon spawns with a usable barrel. This changes as your Scavenging level increases (can be configured in MCM). ALL guns require some level of maintenance in order to get them fully working
- Nimble and other gun trade quests fixes ported from `dev2` so you should hopefully not run into issues with that any more
- Mechanics no longer sell all cleaning kits at supply level 1, so the option to buy cleaning kits is now locked behind upgrading mechanic supply levels. You can still craft all cleaning kits with just a basic toolkit
- Cleaning and repair kits now cost a lot more to buy, and sell for far less (generally less than the cost of crafting it)

## How to install
- Download the mod from the [**releases** tab](https://github.com/veerserif/Tougher-Gun-Repair-GAMMA/releases). Do not extract.
- Install it with Mod Organizer 2:
  - In Mod Organizer 2, go to File -> Install mod...
  - Select this mod
  - Click "OK" on the install popup. The mod should appear at the end of your modlist.
  - Enable the mod.

### Compatibility and requirements


- This mod **requires** GAMMA Guns Have No Condition. It must overwrite files from G.A.M.M.A. Guns Have No Condition, G.A.M.M.A Vices are Free, and G.A.M.M.A. ZCP 1.4 Balanced Spawns
- This mod is likely incompatible with other mods that change how weapon maintenance works. Below are some mods that we know are incompatible; this list is not exhaustive
  -  [Weapon Maintain Features 'n fixes](https://github.com/Bence7661/Serious_Weapon_Maintain_Features)
- This mod was designed around unmodified GAMMA 0.9.3, and will cause strange results if you try to put this on vanilla Anomaly
- We recommend, but don't currently require, the [Workshop Optimization](https://github.com/Bence7661/Serious_Workshop_Optimization) mod

## Credits

This is a collaboration between Serious and Veer. By which I mean one of us wrote nearly all of the mod while the other one made appreciative clapping noises.

- Veerserif's other mods: [find them on Discord](https://discord.com/channels/912320241713958912/1257380080397844533/1257390905560928297)

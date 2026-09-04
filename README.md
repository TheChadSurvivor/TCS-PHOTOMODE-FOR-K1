TCS PHOTO MODE uses ReShade to create a fully functional photo mode for Knights of the Old Republic 1.

## Required

1. **ReShade with add-on support** (OpenGL, installed next to `swkotor.exe` — not a shared ReShade folder).
2. **Knights of the Old Republic 1** (stock / GOG). **KotOR 2 is incompatible.**
3. **Part 1**: https://www.nexusmods.com/kotor/mods/1878

## Installation

1. Install **ReShade with add-on support**.  
   [ReShade Home](https://reshade.me)
2. Apply any **widescreen patches** for KotOR 1.
3. Install **Part 1**. Choose the pack for your card and drop the contents inside **"Move Inside Content to Game Folder"** into your game folder.  
   https://www.nexusmods.com/kotor/mods/1878  
   https://www.nexusmods.com/profile/TheChadSurvivor
4. Download **TCS_PHOTOMODE_V1_GITHUB.zip** from this release. Unzip and copy its contents into the folder that contains `swkotor.exe` (keep `reshade-shaders` and `TCS_PHOTOMODE`).
5. Run **KotOR 1**. (**K2 is incompatible with this mod.**)
6. Open the ReShade menu (**Home**), go to the **Add-ons** tab, open **TCS_PhotoMode**, enable it.
7. Press **Y** to access TCS Photo Mode anytime.
8. Done. Adjust it to your heart's content.

**Author's note:** ReShade must be specific to the game, installed in that game folder, not a shared folder used by multiple games, or there will be conflicts.

## Packs

- **TCS_PHOTOMODE_V1_GITHUB.zip** — KotOR 1 photo mode drop-in

## Credits

Big thanks to Lane's research and decompilation of KotOR. Helped a lot with finding strings and functions.

[LaneDibello/Kotor-Patch-Manager](https://github.com/LaneDibello/Kotor-Patch-Manager) — Patching Framework for Star Wars: Knights of the Old Republic 1 & 2  
LaneDibello (Lane Dibello)

Many thanks also to the OpenKotOR wiki:  
[OpenKotOR/wiki](https://github.com/OpenKotOR/wiki)  
KobaltBlu (James)

Huge thanks to **martymcmodding (Pascal Gilcher)** for their qUINT ReShade effect and shaders.

ReShade add-on API by Patrick Mours.

## License

MIT covers TCS Photo Mode packaging and the TCS add-on only. ReShade headers stay CC0. qUINT shaders remain © Pascal Gilcher / Marty McFly, all rights reserved. Star Wars: Knights of the Old Republic is © Lucasfilm / Disney. This project is not affiliated with BioWare, Lucasfilm, Disney, or ReShade.

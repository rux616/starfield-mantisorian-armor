Mantisorian Armor (Mandalorian-Inspired Mantis Armor Replacer)
==============================================================
Version: 1.0.1

Table Of Contents
-----------------
- Mantisorian Armor (Mandalorian-Inspired Mantis Armor Replacer)
    - Table Of Contents
- Overview
    - Summary
    - Installation
    - Known Issues
- Technical Details
- License
- Credits and Acknowledgements
- Contact


Overview
========

Summary
-------
I thought the idea of a unique spacesuit was cool, but wasn't overly enamored with the looks of the default Mantis Armor. I also didn't really want to literally have Mandalorian armor. So I compromised, and retextured the Shock Trooper Armor, Starborn Helmet, and Deepseeker Pack instead. This is the result.

The layered texture files in (paint.net format - pdn) can be found in the GitHub repository for this project (https://github.com/rux616/starfield-mantisorian-armor).

Installation
------------
NOTE: Modding in Starfield is a bit different by default in that unless you change it, mods are now installed into the "Documents\My Games\Starfield" folder instead of in the game's installation folder.

Manual:
If you _haven't_ disabled Starfield's ability to load mods from the "Documents\My Games\Starfield" folder, extract the archive there.

If you _have_ disabled Starfield's ability to load mods from the "Documents\My Games\Starfield" folder, extract the archive to your Starfield installation folder (typically something like "C:\Games\SteamLibrary\steamapps\common\Starfield") instead.

Mod Manager:
Download and install the archive with either Mod Organizer 2 v2.5.0 Beta 14 or later (MO2 Discord server (https://discord.gg/AKE9wRGpy4), "dev-builds" channel), or Vortex (https://www.nexusmods.com/site/mods/1). I personally recommend Mod Organizer 2 (with the optional Root Builder (https://kezyma.github.io/?p=rootbuilder) plugin to use with SFSE or any other mod that requires files be put directly in the game's installation folder).

Archive Invalidation:
Make sure your `StarfieldCustom.ini` file in the "Documents\My Games\Starfield" folder contains the following:

    [Archive]
    bInvalidateOlderFiles=1
    sResourceDataDirsFinal=

Disabling Mod Loading From "Documents\My Games\Starfield":
NOTE: This is optional. It's also not even necessary with Mod Organizer 2 as it virtualizes everything already.

Make sure your `StarfieldCustom.ini` file in the "Documents\My Games\Starfield" folder contains the following:

    [Display]
    sPhotoModeFolder=Photos

    [General]
    bEnableMessageOfTheDay=0

Then move the contents of the "Documents\My Games\Starfield\Data" folder out of said folder. Put your screenshots folder at "Documents\My Games\Starfield\Photos". The end goal is that the "Documents\My Games\Starfield\Data" folder should be empty.

Known Issues
------------
- The spacesuit clips a little into the helmet around the neck area.
- Some of the detail textures from the original Mantis spacesuit show up on the replacement suit, resulting in some interesting patterning.


Technical Details
=================
Texture Formats:
- ao, mask, metal, rough: BC4 [paint.net: BC4 (Linear, Unsigned)]
- color: BC1 [paint.net: BC1 (sRGB, DX 10+)]
- normal: BC5 [paint.net: not sure, didn't edit]


License
=======
All nif, morph.dat, dds, and pdn files are derived from original Starfield assets, or are wholesale copies of Starfield assets, so BGS own the copyright and control their usage.

For all other content, the following licenses apply:
- All code files are copyright 2023 Dan Cassidy, and are licensed under the GPL v3.0 or later (https://www.gnu.org/licenses/gpl-3.0.en.html).
- All non-code files are copyright 2023 Dan Cassidy, and are licensed under the CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/) license.


Credits and Acknowledgements
============================
hexabit: For a newer NifSkope release that supports the version of nif files that Starfield uses
ElminsterAU: For xEdit
Mod Organizer 2 team: For getting Mod Organizer 2 with Starfield support out the door so quickly
paint.net (https://getpaint.net/): For being a really nice program to do my texture edits in
Nexus Mods: For mod hosting and for the Vortex Mod Manager

Contact
=======
If you find a bug or have a question about the mod, please post it on the mod page at Nexus Mods (https://www.nexusmods.com/starfield/mods/5685), or in the GitHub project (https://github.com/rux616/starfield-mantisorian-armor).

If you need to contact me personally, I can be reached through one of the following means:
- Nexus Mods: rux616 (https://www.nexusmods.com/users/124191) (Send a message via the "CONTACT" button.)
- Email: rux616-at-pm-dot-me (replace `-at-` with `@` and `-dot-` with `.`)
- Discord: rux616 (I am in the Nexus Mods (https://discord.gg/nexusmods), Collective Modding (https://discord.gg/pF9U5FmD6w) ("🔧-chaotic-cognitions" channel), and Lively's Modding Hub (https://discord.gg/livelymods) servers, amongst others. Make sure to "@" me.)

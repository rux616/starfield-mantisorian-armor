Mantisorian Armor
=================
by rux616

Version: 1.2.0

Table Of Contents
-----------------
- [Mantisorian Armor](#mantisorian-armor)
    - [Table Of Contents](#table-of-contents)
- [Overview](#overview)
    - [Summary](#summary)
    - [Compatibility](#compatibility)
    - [Known Issues](#known-issues)
- [Installation](#installation)
    - [Archive Invalidation](#archive-invalidation)
    - [Requirements](#requirements)
    - [Recommendations](#recommendations)
    - [Upgrading](#upgrading)
    - [Mod Manager](#mod-manager)
    - [Manual (NOT RECOMMENDED)](#manual-not-recommended)
- [Technical Details](#technical-details)
- [License](#license)
- [Credits and Acknowledgements](#credits-and-acknowledgements)
- [Contact](#contact)


Overview
========

Summary
-------
(Mandalorian-inspired Mantis spacesuit replacer.)

Compatible with Starfield v1.11.36+.

I thought the idea of a unique spacesuit was cool, but wasn't overly enamored with the looks of the default Mantis Armor. I also didn't really want to literally have Mandalorian armor. So I compromised, and retextured the Shock Trooper Armor, Starborn Helmet, and Deepseeker Pack instead. This is the result.

([TOC](#table-of-contents))

Compatibility
-------------
Should be mostly compatible with pretty much everything, even mods that alter the stats of the Mantis spacesuit. With that being said, if another mod alters the file paths of the suit models, that will break this mod.

([TOC](#table-of-contents))

Known Issues
------------
- The spacesuit clips a little into the helmet around the neck area.
- Some of the detail textures from the original Mantis spacesuit show up on the replacement suit, resulting in some interesting patterning.

([TOC](#table-of-contents))


Installation
============

Archive Invalidation
--------------------
Make sure your `StarfieldCustom.ini` file in the "Documents\My Games\Starfield" folder (or your profile folder if using a mod manager and profiles) contains the following:

    [Archive]
    bInvalidateOlderFiles=1
    sResourceDataDirsFinal=

([TOC](#table-of-contents))

Requirements
------------
None.

([TOC](#table-of-contents))

Recommendations
---------------
None.

([TOC](#table-of-contents))

Upgrading
---------
When upgrading non-major versions (for example v2.something to v2.something-else), you don't need to do anything except replace the installed mod files.

When upgrading major versions (for example v1.whatever to v2.whatever), you need to do a clean install:
- Open the game and load your latest save
- Save your game, then quit
- Uninstall the previous version of the plugin and all its files
- Open the game and load your last save
- You will see a warning about missing the plugin you just uninstalled, choose to continue
- Save your game again, then quit
- Install the new version of the plugin

([TOC](#table-of-contents))

Mod Manager
-----------
Download and install the archive with either [Mod Organizer 2](https://github.com/ModOrganizer2/modorganizer/releases) (version 2.5.0 or later) or [Vortex](https://www.nexusmods.com/site/mods/1). I personally recommend Mod Organizer 2 (with the optional [Root Builder](https://kezyma.github.io/?p=rootbuilder) plugin to use with SFSE or any other mod that requires files be put directly in the game's installation folder).

([TOC](#table-of-contents))

Manual (NOT RECOMMENDED)
------------------------
Extract the archive to your Starfield installation's "Data" folder (typically something like "C:\Games\SteamLibrary\steamapps\common\Starfield\Data"). Add the plugin file names to your plugins.txt file if they aren't already there, making sure the ones you want enabled are preceded with `*`.

([TOC](#table-of-contents))


Technical Details
=================
Texture Formats:
- ao, mask, metal, rough: BC4 [paint.net: BC4 (Linear, Unsigned)]
- color: BC1 [paint.net: BC1 (sRGB, DX 10+)]
- normal: BC5 [paint.net: not sure, didn't edit]

([TOC](#table-of-contents))


License
=======
All nif, morph.dat, dds, and pdn files are derived from original Starfield assets, or are wholesale copies of Starfield assets, so BGS own the copyright and control their usage.

For all other content, the following licenses apply:
- All code files are copyright 2023 Dan Cassidy, and are licensed under the [GPL v3.0 or later](https://www.gnu.org/licenses/gpl-3.0.en.html).
- All non-code files are copyright 2023 Dan Cassidy, and are licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

([TOC](#table-of-contents))


Credits and Acknowledgements
============================
hexabit: For a newer NifSkope release that supports the version of nif files that Starfield uses
ElminsterAU: For xEdit
Mod Organizer 2 team: For getting Mod Organizer 2 with Starfield support out the door so quickly
[paint.net](https://getpaint.net/): For being a really nice program to do my texture edits in
Nexus Mods: For mod hosting and for the Vortex Mod Manager
jmpz11: For creating the amazing [Starfield .nif Mesh Path Migration Tool for SF 1.11.33](https://www.nexusmods.com/starfield/mods/9234), allowing a swift transition to Starfield v1.11.36+
Noggog: For Spriggit

([TOC](#table-of-contents))


Contact
=======
If you find a bug or have a question about the mod, please post it on the [mod page at Nexus Mods](https://www.nexusmods.com/starfield/mods/5685), or in the [GitHub project](https://github.com/rux616/starfield-mantisorian-armor).

If you need to contact me personally, I can be reached through one of the following means:
- **Nexus Mods**: [rux616](https://www.nexusmods.com/users/124191) (Send a message via the "CONTACT" button.)
- **Email**: rux616-at-pm-dot-me (replace `-at-` with `@` and `-dot-` with `.`)
- **Discord**: rux616 (user ID 234489279991119873) - make sure to "@" me
    - [Lively's Modding Hub](https://discord.gg/livelymods)
    - [Nexus Mods](https://discord.gg/nexusmods)
    - [Collective Modding](https://discord.gg/pF9U5FmD6w) ("🔧-chaotic-cognitions" channel)
    - [Starfield Modding](https://discord.gg/6R4Yq5KjW2)

([TOC](#table-of-contents))

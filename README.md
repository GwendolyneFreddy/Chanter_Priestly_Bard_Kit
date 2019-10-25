
![Latest Release](https://img.shields.io/static/v1?label=release&message=v2.0.0&color=darkred)<a name="top" id="top">
![Platform](https://img.shields.io/static/v1?label=platform&message=windows&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French&color=limegreen)

<div align="center"><h1></a> (WIP)</h1>

<h3>A mod hosted by Spellhold Studios for Baldur's Gate II: Throne of Bhaal, EE games (xcept Planescape),
Baldur's Gate Trilogy and EET<h3>

</div><br />


**Original Author:** Adul  
**Mod Website and Forum:** <a href="http://www.shsforums.net/topic/39877-chanter-priestly-bard-kit-v20/">Spellhold Studios</a><br /><br />


<div align="center">
<a href="#intro">Overview</a> &#x2B25; <a href="#compat">Compatibility</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Components</a> &#x2B25; <a href="#credits">Credits</a> &#x2B25; <a href="#versions">Versions History</a></center></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

This mod adds a new bard kit. I decided to create it because I thought it would fit well into the start of the game (talking about BG1). Candlekeep is famous of its monastery and you can see a couple of chanters there. I figured it would make a fun kit, a type of bard who is more priestly than wizardly.


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on the following Infinity Engine games: the original Baldur's Gate II (BG2 or just SoA) with the Throne of Bhaal (ToB) expansion, Baldur's Gate II: Enhanced Edition (BG2EE), the conversion projects Baldur's Gate Trilogy (BGT) and Enhanced Edition Trilogy (EET).

This is a WeiDU mod, and therefore should be compatible with all WeiDU mods. If you encounter any bugs, please report them on the forum!<br>


To ensure compatibility, you should install this component AFTER the BG2 Fixpack. (If you install both mods, that is.)
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

<em>If you've previously installed the mod, remove it before extracting the new version. To do this, run **setup-chanter.exe**, uninstall the previously installed main component and delete the chanter folder.</em>

<em>When installing or uninstalling, **do not close the DOS window** by clicking on the **X** button! Instead, press the **Enter** key whenever instructed to do so.</em>

**Disable any antivirus** or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.

## 

#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.

## 

#### Windows

Extract the contents of the mod archive into the folder of the game you wish to modify (<em>the folder which contains the "CHITIN.KEY" file</em>), using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be a chanter folder and a setup-chanter.exe file in your game folder. To install, simply double-click **setup-chanter.exe** and follow the instructions on screen.

Run **setup-chanter.exe** in your game folder to reinstall, uninstall or otherwise change the component settings.

## 

#### Note for Complete Uninstallation

In addition to the methods above for removing individual components, you can completely uninstall the mod using **`setup-chanter --uninstall`** at the command line to remove all components without wading through prompts.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components

he installer includes the following components. The number of each is the component DESIGNATED number which gives it a fixed install position and allows automated installers to specify component choices.<br /><br />


**0. Chanter Kit**<br />

This is the main component which installs the Chanter Kit.

Chanters are monk-priests who specialize in the keeping and telling of ancient lore. Imbued by divine power and primordial secrets, their chants bear powerful magical properties that can aid allies or smite enemies.


Advantages:
- Has access to a selection of priest spells.
- Can cast spells in armor.
- Immune to effects that cause casting failure.
- Has access to a number of chants. A chant works like a bard song and affects all nearby allies.
	- Level 1: Sanctum (+2 to all saves, protection from fear)
	- Level 6: Contegitas (+33% fire, cold, lightning, and acid resistance)
	- Level 9: Omnimens (immunity to charm, confusion, and hold effects)
	- Level 14: Salve (heal 1 HP each round, immunity to level drain)
	- Level 17: Veritas (removes all nearby illusions and grants true seeing)


Disadvantages:
- Cannot learn or cast wizard spells.
- Cannot pick pockets.
- No proficiency in two-weapon fighting.

<em>A selection of priest spells</em> means all cleric spells from level 1 to level 6. He cannot cast level 7 spells.

Chants work like bard song, except that you can switch between them any time you wish. This makes the chanter a very useful utility character at higher levels, with chants to help in every situation.

He also has several new HLAs (high level abilities) including two "quest" level spells, a powerful offensive chant, an ability that replaces low level chants with more powerful versions, bonus spell slots, and a unique monk-themed talent. I've removed the thief-like abilities, as they really didn't fit this kit. Alchemy, Scribe Scrolls, and Magic Flute have been altered (only for the chanter, does not affect other characters) to better fit this kit.

All of the chanter's new abilities and spells have got new icons.


**Please note that this mod technically adds 2 kits to the game, although you will only ever see one of these during character creation.**

## 

**10. Chanter gains cleric stronghold instead of bard one**<br />

This optional component requires the main component to be installed, and allows a chanter protagonist to claim the temple stronghold. As with clerics, the character's alignment determines which temple approaches them.

Without this component the chanter gains the playhouse like all bards do.
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

#### Author: <a href="http://adul.net/">Adul</a>


#### Special Acknowledgements to:

- Gwendolyne: Fixed translations and released version 2.0.0.
- Deratiseur: Provided French translation, the EE compatible version and released version 1.5.
- Special thanks to GeN1e, Jarno Mikkola, Icendoan, smoky tune, the bigg, and Zauberbratsche at the SHS forums for their help and/or advice..

If you wish to translate the mod, have a suggestion, or should encounter any bugs, please report them to the maintainers at the <a href="">mod forum</a>.</br>


#### Copyrights Information

###### Chanter Kit is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Abdul, based on material from the game Baldur's Gate II and its expansion.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.
###### All other trademarks and copyrights are the property of their respective owners.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Versions History

##### Version 2.0.0 (, 2019)

- Renamed Setup-ChanterKit.tp2 -> chanterkit.tp2 to support AL|EN's "Project Infinity".
- Added chanterkit.ini metadata file to support AL|EN's "Project Infinity".
- Reorganized mod architecture tree: created or renamed folders to sort files according to their types.
- Reorganized component (DESIGNATED number).
- Added REQUIRE_PREDICATE process to avoid installing the mod in inaccurate games.
- Replaced AUTHOR keyword with SUPPORT.
- Updated and renamed readme file to <em>chanterkit-readme-%LANGUAGE%</em>.
- Updated French and English translations (Gwendolyne).

## 

##### Version 1.5 (August 3, 2019)

- Traified and adapted mod for EE games (by Deratiseur).
- Updated WeiDU installer to v246.

## 

##### Version 1.4a (June 15, 2011)

- Fixed a bug that caused first level chanter characters to cast Magic Missile on themselves after character creation and when switching between chants (don't ask).

## 

##### Version 1.4 (June 14, 2011)
- Added a new component that allows chanters to claim the cleric stronghold instead of the bard one.
- Added new functionality to restore deleted spells to the chanter's spellbook at level up and when switching between chants ('Quest' level spells cannot be restored this way).
- Fixed an error that caused some of the chanter's abilities to expire under certain conditions.
- The chanter's Alchemy, Scribe Scrolls, and Magic Flute high level abilities have been altered to produce items more relevant to the chanter's role.
- Increased the extent of the elemental resistances bestowed by the Contegitas chant from 20% to 33%.
- Reduced the total number of spells a level 40 chanter can memorize by one spell for each spell level.
- Renamed the following chanter abilities:
	- Consilium   -> Omnimens
	- Magic Flute -> Mystic Flute
	- Purgatorium -> Expulses
	- Sanitas     -> Salve
- Changed in-game descriptions for several chanter abilities.

## 

##### Version 1.3a (June 8, 2011)

- Fixed a critical error introduced in version 1.3.

## 

##### Version 1.3 (February 25, 2011)

- Fixed a bug that prevented a new chanter character from being set up properly at the start of the game.

## 

##### Version 1.2 (May 7, 2010)

- Solved an issue that caused character creation to become stuck at the spell selection screen unless starting a chanter at level 1.

## 

##### Version 1.1 (May 3, 2010)

- Fixed an error that prevented the chanter from gaining access to the Sanitas chant at level 14.

## 

##### Version 1.0 (April 19, 2009)

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>

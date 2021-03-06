# TGAAC Mod
Mod of the PC/Steam version of The Great Ace Attorney Chronicles

**This initial alpha version only contains script changes - names and places, no texture mods. The script changes are not optional in this initial version, they will be in the next release.**

**This does not yet contain our fan-translated English script.**

For a full list of changed names/terms, see [ScriptChanges.md](https://github.com/ScarletStudy/DGS-PC/blob/main/ScriptChanges.md).

## Download
Get the latest version from [Releases](https://github.com/ScarletStudy/DGS-PC/releases). The filename is `dinput8.zip`. Unpack the files as directed in the next section.

## Installation
* Right-click _The Great Ace Attorney Chronicles_ in your Steam Library > Manage > Browse local files
* If you're using Admiral Curtiss' [dgs hackfix](https://github.com/AdmiralCurtiss/dgs_hackfix), rename that file from `dinput8.dll` to `hackfix.dll`
* Put `dinput8.dll` in the same folder as `TGAAC.exe`

## Notes
* Our mod is fully compatible with Admiral Curtiss' [dgs hackfix](https://github.com/AdmiralCurtiss/dgs_hackfix), which is really worth trying out if you haven't done so yet. Our mod will chainload it if it detects it. 
* This mod is developed and tested for the WorldWide (English script) and the Japanese (Japanese and English script) version of the game
* **This is an alpha version of our planned mod.** It doesn't contain anything besides the script mod engine so far, it's mostly to find bugs and words we missed. Textures are not yet replaced by this mod.

## Known Issues
* A puzzle in the final episode of DGS2 still requires you to enter the offically localized name
* The script will bleed out of bounds in several places. This will be fixed after we've swapped out the font.

## Planned Features
* Texture replacements
* New font
* Delta patching on initial run
* Optional script modifications - that means that you can select which names/terms you want to replace and which ones you want to remain unchanged
* In-game menu for options and possibly debugging and game modding
* Alternative scripts - this includes support for our fan-translated English script and other languages

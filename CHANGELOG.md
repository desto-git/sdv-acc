## 6.0.4-1

Updated to 6.0.4, which contains the following changes compared to 5.22.

**Changelog in content.json**
- 2.0.0 Major Update! Stardew Valley 1.5 came out, and now January 2021, we've got a new CP mod in works. Glitches *may* occur
- 2.0.1 Removed event dialogue changes until further notice, updated ClothesTherapyCharacters to be actually replaced.
- 2.0.2 Updated cursors files.

**Characters**
- Add beach sprites of all applicable characters
- Caroline: Fix hand colors of some sprites
- Clint: Add beard to match his portrait
- Jodi: Minor color adjustment to the outline of the hair
- Krobus: Remove some misplaced white pixels
- Lewis: Update head for a better fit for his hat
	- Edit by me: Revert one of the tea sipping sprites
- Linus: Remove some "ears" on the side (the actual ears are on top after all)
- Marnie: Make her hair more vibrant
- Pam: Add missing sleeves, and slightly adjust fishing bobble
- Penny: "Fix nose"?
	- Edit by me: Revert the change, but keep the shadow on the throat
- Pierre: New hairstyle
- Robin: Fix eye color, minor hair color change, and some corrupt sprites?
	- Edit by me: Revert the hair color and corrupt sprites
- Sebastian: Fix outline of hands of one sprite
- Shane: Add missing tail and fix throat
- Willy: Make head bulkier, and weird hat on some walking sprites
	- Edit by me: Revert the weird hat
- Add new event sprites for Abigail, Caroline, George, Lewis, Linus, Marnie, Pam, Robin, Willy
	- Edit by me: Change Robin's hair color to match the previous version
- New characters: Bear, Birdie, Leo, Professor Snail
- Add Dick (Willy) and "KrobusRaven" (is that a minigame?)
- Add `farmer_base.xnb`
	- Edit by me: Revert, it is not used

**LooseSprites**
- Update skeleton sprite to look bovine in `boardGame.png`
- Add new CC Bundle sprites
- Add new TV channel (At least I think that what it is)
- Add witch on a broom
- Add a new mermaid sprite

**Maps**
- Add festival igloo
- Add pirates
- Add flu poster

**Portraits**
- Add beach portraits of all applicable characters
- Alex: Tweak across all portraits
- Elliot: Tweak across all portraits
- Haley: Update eyebrows of one portrait
- Jodi: Fix hair of one portrait
- Lewis: Add a new expression
- Linus: Add two new expressions
- Pierre: New hairstyle
- Robin: Add neck fluff, two new expressions and move some portraits around
- Shane: Tweak clothing and neck
- Vincent: Tweak expressions and proportions

**Miscellaneous**
- Move event changes from inline `content.json` into a full `.xnb` patch
- By me: Reduced file size even further (~1.8MB)

## 5.22.1

- Fix flickering fireplace and chessboard pattern water tiles

## 5.22.0

- Improve compatibility with other mods by using "EditImage" instead of "Load"
- Split content.json into multiple files
- Get rid of the "libpng warning: iCCP: known incorrect sRGB profile"
- Add UpdateKey to manifest.json
- Prefix mod folder with "[CP]" to follow the community-standard
- Drastically reduce file size (18.8MB -> 2.3MB) via:
	- Remove redundant multi-language versions (they inherit the changes)
	- Remove unaltered parts of images

## pre manifest.json

These changes were logged as a comment in the content.json.

- 1.0.1 Removed farmer bases (meant for a different mod) and added two event changes to coincide with this universe of furries (Witch mentions humans oops)
- 1.0.0 Started the CP version with the above mentioned, to be compatible with 1.4 update of SDV.
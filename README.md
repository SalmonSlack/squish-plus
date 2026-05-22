# ![Squish+ Mod Logo, credit to https://www.textstudio.com/](https://github.com/SalmonSlack/squish-plus/blob/main/Logo.png)

## 📄 About
Squish+ is a mod created for SM64 Co-op Deluxe! It expands on the existing squish feature in SM64, making it more dynamic, more interactive, and more cartoony! Players can now find themselves squished into a variety of poses, all based on the pose they were in the moment they got squashed! This mod adds new sound effects, new squish physics, and new enemy interactions that will leave players flatter than ever before! Check out the [trailer](https://drive.google.com/file/d/1Zh6yISxlmxnd6XwUKODs0lXvTOFLVoE-/view?usp=sharing) if you haven't already seen it!

If you are new to SM64 Co-op Deluxe, check out the [Setup Guide!](#-setup-guide-windows) It has step-by-step instructions for getting this mod running on your computer!

If you enjoyed using this mod or want to show support, sharing this or dropping me a comment on my socials to let me know what you think would mean a lot! I may expand on this mod or try and make mods like this for other games in the future if people like this one!

Finally, I want to end off this section with a big thanks to `YOU` for checking out this mod! SM64 holds a special place in my heart, and getting to share this with the wonderful community I've been a part of for so many years is a wonderful feeling!
<br/><br/>

## 🛠️ Setup Guide (Windows)
1. Go to [the team's official GitHub page](https://github.com/coop-deluxe/sm64coopdx/releases/tag/v1.3.2), then scroll to the bottom of the page and download the appropriate version of the game for your system (e.g. `sm64coopdx_Windows_DirectX.zip`)
2. Extract the ZIP file, and run sm64coopdx.exe. It should notify you that you need an SM64 ROM
3. Obtain a Super Mario 64 ROM (I can't legally say where to get one, but just make sure it is a .z64 file)
4. Drag the ROM directly into your SM64 Co-op DX game window
5. Download `squish-plus.zip` from [this page](https://github.com/SalmonSlack/squish-plus/blob/main/squish-plus.zip) by entering `Ctrl-Shift-S` or by clicking the three dots towards the right of the page
6. Drag the whole ZIP file directly into your SM64 Co-op DX game window
7. Click the following Menu buttons: `Host -> Mods -> Squish+ -> Back -> Settings -> Skip Intro Cutscene -> Back -> Host`
8. Once you've loaded in, click **D-Pad Down** (End key by default). If Mario squishes, then you're all set!

Once you verify the mod is working, I recommend setting `Interpolation` to `Fast` by returning to the main menu and clicking `Options -> Display -> Interpolation.` This fixes a lot of visual bugs! From there, I suggest configuring your controls, and going to the [official modding page](https://mods.sm64coopdx.com/mods/) to find some fun [character models](https://mods.sm64coopdx.com/mods/categories/custom-characters.4/) to mess around with! Or you could even [make your own!](https://github.com/coop-deluxe/character-template?tab=readme-ov-file#character-templates-for-coop-deluxe) If you enable the pre-installed `Character Select` and `[CS] Extra Characters` mods, you can select the ones you've downloaded and more with the in-game `/char-select` command accessed by hitting the `Enter` key!
<br/><br/>

## 🎮 Mod Instructions / Controls
- `D-Pad Down` - ✨ Self Squish Button ✨ You can use this almost anytime you like! It makes for an easy means of squashing yourself to whatever surfaces you wish, whether there's an enemy around or not to do it for you!
  
- `A Button` - ✨ Soft Restore Button ✨ This button is how you can organically recover from the `squished` state. You cannot `soft restore` yourself if you are out of health, have been `squished` for less than a number of seconds, or if you are underneath a `Surface Object` (Thwomp, Whomp, etc).
  
- `D-Pad Up` - ✨ Hard Restore Button ✨ Use this button if you ever find yourself soft-locked / unable to restore or respawn while in the `squished` state. This acts as an emergency button in case you encounter a soft-lock because of the mod 💦
  
- `D-Pad Left` - ✨ Set Pose Preset ✨ This button captures your character's current animation and frame, allowing you to 'freeze' yourself in that position later if you have a particular pose you want to be squished in.
  
- `D-Pad Right` - ✨ Toggle Preset Pose On/Off ✨ This button will toggle "Pose Mode," a mode that will lock your character in whichever animation and frame you selected earlier with the **Set Pose Preset** button. This is a way for you to more easily squish yourself in whichever pose you like! I'd like to expand on this feature in the future to make it easier to select the exact animation, frame, and angle you want to be squished in as well.

- `Squish+ Mod Menu` - ✨ Modify Your Squishing Experience ✨ From the SM64 DX pause menu (Accessed with Pause -> Right-Bumper, Defaults are Spacebar -> Right Shift), you'll see a button labelled either `Squish+` or `Mod Menu`. Entering this menu will give you access to a bunch of customization options for the mod!

Feel free to use additional mods in tandem with this one! However, I suggest sticking to level mods (such as the pre-installed Star Road mod), or [character mods](https://mods.sm64coopdx.com/mods/categories/custom-characters.4/) for the smoothest experience! I've only tested compatibility with a [small handful of behavior mods](#-compatible-mods).
<br/><br/>

## 🧩 Mod Compatibility
I'll add onto this list as I do more testing, but for now, assume any character mods and level packs are compatible, and any behavior altering mods `not` listed here are semi-incompatible or incompatible!

### ✅ Compatible Mods
- [Free Camera](https://mods.sm64coopdx.com/mods/freecamera.457/): I recommend adding this mod to your game in case you ever want to capture a specific angle you can't otherwise get with the vanilla camera!
- [Noclip](https://mods.sm64coopdx.com/mods/noclip.30/)
- [King's DevTools](https://mods.sm64coopdx.com/mods/kings-devtools.339/): Default button mappings use the D-Pad, which causes the actions from `Squish+` and `DevTools` to happen at the same time. (e.g. `D-Pad Down` squishes you AND opens the map select menu) This can be fixed by having the server host disable the `D-Pad Actions` mod option.

### ⚠️ Semi-Compatible Mods
- Arena (Comes built into Coop Deluxe): Lots of issues and unexpected behaviors when interacting with this mode, however the host options hopefully help offset some of the glaring problems! I would like to explore the possibility of making this mode more compatible with Squish+ in future updates!
- [MarioHunt](https://mods.sm64coopdx.com/mods/mariohunt.8/): The main issue in MarioHunt around respawning while flat has been fixed, however I don't feel comfortable calling it compatible yet! Just make sure you have the Squish+ settings for auto restore enabled, and the option to Allow D-Pad usage to disabled for the best experience!

### ❌ Incompatible Mods
- Player Resizing Mods: Squish+ currently assumes the player's default scaling is 1 on the x, y, and z axes, so adjusting these base values will lead to unexpected behaviors.
<br/><br/>

## 🕑 Reverting
If you find yourself wanting to return to an old version of the mod, you can follow these steps to get the old version back on your system!
1. Navigate to `squish-plus.zip` [history page](https://github.com/SalmonSlack/squish-plus/commits/main/squish-plus.zip)
2. Click on one of the titles, this should take you to a new page
3. Click the three dots towards the right of the page, and click `View File`
4. Enter `Ctrl-Shift-S` or click the three dots towards the right of the page and click `Download`
5. Open SM64 Co-op Deluxe
6. Drag the `squish-plus.zip` file directly into your game window
7. This should automatically update your mod to the version you just downloaded!
<br/><br/>

## ✨ What's New
### [v1.10](https://github.com/SalmonSlack/squish-plus/releases/tag/v1.1)
<sup>05/20/2026</sup>

It's been awhile! Thanks for the patience and I hope folks enjoy this new update! We got a lot of new stuff, and there are extra details about these new features in the [release page](https://github.com/SalmonSlack/squish-plus/releases/tag/v1.1) but for a TLDR, we have:

### Features
- 🍃 **Fluttering** 🍃 Players can now flutter through the air like a piece of paper when restoring from a flattening!
- 💬 **Deflated Alerts** 💬 Players can now see alert messages appear when they get defeated by a squishing hazard!
- 🪨 **Custom Enemy Behaviors** 🪨 Players can experience whole new enemy behaviors with `Thwomps` and `Spindels`!

A note on Koopa the Quick - Updating your `Character Select` version to `v1.16.3` will allow Koopa the Quick to squish players again. Just download `character-select-coop.zip` from the following page and drag the ZIP directly into your game window to update it: https://github.com/Squishy6094/character-select-coop/releases/tag/v1.16.3

### Adjustments
- The Squish+ Mod Menu has returned and has one purpose: To direct players to the new menu! Sometimes folks find themselves checking for the mod menu via the Coop DX pause menu, and this button serves as a handy way to reach the new menu without any special commands / button presses!
 
### Bug Fixes
- Players can now restore under water and above water without teleporting to the water's surface
- `Faster Swimming` Mod is now compatible with Squish+, meaning no more getting squished for daring to swim too fast!
- Fixed an issue where Spindels wouldn't spread the player when rolling a certain direction

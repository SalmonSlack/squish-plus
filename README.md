# Super Mario 64 Co-op Deluxe Squish+ Mod

## 📄 About
Squish+ is an SM64 Co-op Deluxe Mod that expands on the existing squish feature, making it more dynamic, more interactive, and more cartoony! Players can now find themselves squished into a variety of poses, all based on the pose they held the moment they got squashed! New sound effects, new squish physics, and new enemy interactions that will leave players flatter than ever before!

If you are new to SM64 Co-op Deluxe, check out the [Setup Guide!](#-setup-guide-windows) It has step-by-step instructions for getting this mod running on your computer!

If you enjoyed using this mod or want to show support, sharing this or dropping me a comment on my socials to let me know what you think would mean a lot! I may expand on this mod or try and make mods like this for other games in the future if people like this one!

Finally, I want to end off this section with a big thanks to `YOU` for checking out this mod! SM64 holds a special place in my heart, and getting to share this with the wonderful community I've been a part of for so many years is a wonderful feeling!
<br/><br/>

## 🛠️ Setup Guide (Windows)
1. Download SM64 Co-op DX by clicking the green `Code` button on [the team's official GitHub page](https://github.com/coop-deluxe/sm64coopdx), then click `Download ZIP`
2. Extract the ZIP file, and run sm64coopdx.exe. It should notify you that you need an SM64 ROM
3. Obtain a Super Mario 64 ROM (I can't legally say where to get one, but just make sure it is a .z64 file)
4. Drag the ROM into your SM64 Co-op DX application
5. Download [squish-plus.zip]("") by clicking the download icon towards the right of the page
6. Drag the whole ZIP file into your SM64 Co-op DX application
7. Click the following Menu buttons: `Host -> Mods -> Squish+ -> Back -> Settings -> Skip Intro Cutscene -> Back -> Host`
8. Once you've loaded in, click **D-Pad Down** (End key by default). If Mario squishes, then you're all set!

From here, I suggest [configuring your controls](""), and going to the [official modding page](https://mods.sm64coopdx.com/mods/) to find some fun character models to mess around with! Or you could even [make your own!](https://github.com/coop-deluxe/character-template?tab=readme-ov-file#character-templates-for-coop-deluxe) If you enable the pre-installed `Character Select` and `[CS] Extra Characters` mods, you can select the ones you've downloaded and more with the in-game `/char-select` command!
<br/><br/>

## 🎮 Mod Instructions / Controls
- `D-Pad Down` - ✨ Self Squish Button ✨ You can use this almost anytime you like! It makes for an easy means of squashing yourself to whatever surfaces you wish, whether there's an enemy around or not to do it for you!
  
- `A Button` - ✨ Soft Restore Button ✨ This button is how you can organically recover from the `squished` state. You cannot `soft restore` yourself if you are out of health, have been `squished` for less than a number of seconds, or if you are underneath a `Surface Object` (Thwomp, Whomp, etc).
  
- `D-Pad Up` - ✨ Hard Restore Button ✨ Use this button if you ever find yourself soft-locked / unable to restore or respawn while in the `squished` state. This acts as an emergency button in case you encounter a soft-lock because of the mod 💦
  
- `D-Pad Left` - ✨ Set Pose Preset ✨ This button captures your character's current animation and frame, allowing you to 'freeze' yourself in that position later if you have a particular pose you want to be squished in.
  
- `D-Pad Right` - ✨ Set Animation to Preset ✨ This button will freeze you in whichever animation and frame you selected earlier with the **Set Pose Preset** button, making it easier to squish yourself in a particular pose whenever you like. (Default pose is spread-eagle).

- 

Feel free to use additional mods in tandem with this one! However, I suggest sticking to level mods (such as the pre-installed Star Road mod), or [character mods](https://mods.sm64coopdx.com/mods/categories/custom-characters.4/). I've only tested compatibility with a [small handful of behavior mods](#-compatible-mods).

If you're able to consistently replicate a bug, don't hesitate to [fill out a bug report](https://docs.google.com/forms/d/e/1FAIpQLScznpjr9QTrfvurq5ktppkQWYIKzjsfdZWjz0u9a9tsZkZtcQ/viewform?usp=header) with reproduction steps, it helps me a lot! Just make sure to read the [bug reporting guide](#-bug-reporting-guide) first!
<br/><br/>

## 🐛 Bug Reporting Guide
Reporting bugs you come across helps me make this mod as enjoyable as possible! This guide exists to explain how best to go about reporting issues you find! Before you spend time filing a report, check out the [Trello Board](https://trello.com/b/89uM80j1/squish), as it's possible the bug is already in the process of being fixed!

There's no 'correct' way to fill out a report, but including enough details for me to replicate the bug on my own computer is a good rule of thumb! Here are two examples of great bug reports:
```
When I throw a Chuckya while standing right up against a ledge, the game teleports me to the ground below and squishes me.

Reproduction Steps:
1. Go to Tall Tall Mountain
2. Pick up the Chuckya
3. Get as close to the ledge as you can
4. Turn to face away from the ledge
5. Throw the Chuckya
```
This report includes a helpful description of the issue and reproduction steps, making it a lot easier for me to reproduce the issue!  
<br/>
```
I keep getting softlocked whenever I exit the boo level while squished. It happens every time I press 'exit level' while flat.
```
Keeping things short and sweet like this is completely fine as well! As long as there's enough information for me to attempt to replicate the bug, it's a great bug report!
<br/>
<br/>

### What Qualifies as a Bug?
I realize what does and does not qualify as a bug is very subjective, so I put together a few questions to help you decide if it's worth spending your time filing a report or not!

If the answer is `yes` to any of these, I would consider it a bug!
- Does the character behave in a way that doesn't make sense for the mod? (For example: Pressing the `Self Squish Button` button jumps you all the way to the **ceiling** instead of the **floor**)
- Is there a de-sync between you and another player? (For example: Player 2 sees themselves squished to a Thwomp, but you see Player 2 squished to a completely different Thwomp)
- Are you forced to use the `Hard Restore Button` to break out of a soft-lock? (For example: You are unable to exit a level while flat, and have to pop into shape using the `Hard Restore Button` before you're allowed to exit)
<br/>

On the flipside, if the answer is `yes` to any of these questions, I would `not` consider it a bug!
- Is this issue related to button mappings between this mod and another mod? (For example: Pressing the `Hard Restore Button` also turns on `Invincibility` mode in the `DevTools` mod)
- Is this an issue related to geometry / how the player 'sticks' to a surface while squished? (For example: When squished to the corner of a Thwomp, most of the player levitates away from the Thwomp's surface)
- Is this an issue related to how a specific character's animations or model interact with the mod? (For example: The `Bowser` player model clips through the ground if squished during the ground pound animation)
<br/>

If you're unsure if something qualifies as a bug or not, feel free to [submit a bug report](https://docs.google.com/forms/d/e/1FAIpQLScznpjr9QTrfvurq5ktppkQWYIKzjsfdZWjz0u9a9tsZkZtcQ/viewform?usp=header) anyway! I'd prefer an excess of reports as opposed to no reports at all! Lastly, thank you for taking the time to read this guide, and thank you in advance if you end up filing a bug report!
<br/><br/>

## ✨ What's New
### v1.0 - (11/01/2025)
- 🎊 Official Release! 🎊
<br/><br/>

## 🧩 Mod Compatibility
I'll add onto this list as I do more testing, but for now, assume any character mods and level packs are compatible, and any behavior altering mods `not` listed here are incompatible!

### ✅ Compatible Mods
- [Noclip](https://mods.sm64coopdx.com/mods/noclip.30/)

### ⚠️ Semi-Compatible Mods
- [King's DevTools](https://mods.sm64coopdx.com/mods/kings-devtools.339/): Default button mappings interfere with
- [Free Camera](https://mods.sm64coopdx.com/mods/freecamera.457/): Pressing 'A' while in Freecam mode restores the player, I recommend navigating the freecam with movement and camera rotation controls only

### ❌ Incompatible Mods

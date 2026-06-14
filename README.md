# Metroid-Dread-Manual-Archipelago-Randomizer
A manual randomizer and map tracker for Metroid Dread designed for the Archipelago Multiworld Randomizer.

# How to Play
This manual is designed for use with Poptracker, so you will need both [Archipelago Randomizer](https://github.com/ArchipelagoMW/Archipelago/releases) (and the Manual Client), as well as the current release of [Poptracker](https://github.com/black-sliver/PopTracker/releases). For more information on what the Archipelago Multiworld randomizer or Manual games are, see their respective GitHub pages.

If you would prefer not to use the Poptracker, refer to IGN's guide for the names of checks. There are a number of innacuracies in their guide with regards to when items are reachable (OVER 50, I counted when testing/editing the apworld), so this isn't ideal.

Before you start, there are a few things you should note:
1. **Key upgrades are progressive and are labelled "Progressive Key Items" by the randomizer.** Each key upgrade is obtained in a specific order (see below), and if you need a certain item to get to a location, you also need all items before it. Since you still need to collect the items in game, this happens to be (based on my testing) the best and simplest way to reflect that in the randomizer.
2. **To get each key upgrade, you need to unlock it first** (i.e. to unlock the Charge Beam check (as well as collect the Charge Beam in game), you need to receive the first Progressive Key Item, the second for Spider Magnet, etc.). This does technically mean these checks cannot have their original item; however, since you are typically locked in the room you obtain the upgrade until you use it, I felt this made the most sense. **The same applies for the Pulse Radar.**
3. **Energy, missile, and power bomb tanks can be collected as usual in game, provided you follow the rules below.**
    - **If you lose more energy tanks than you've recieved from the randomizer, you get a game over.** Either run into an enemy until Samus dies, or reload the last checkpoint through the menu accessed with the minus button.
    - **You may not use more missiles or power bombs than you've received from the randomizer.**
    - **Energy tanks are not accounted for in logic (not yet, at least).** I tried to avoid including hellruns in logic, but there are a few instances where they are expected (mostly when it extends to just 1 screen). These checks don't tend to need much energy, but a few can take a couple energy tanks to get. **If you are logically expected to be able to do one of these checks but haven't been sent the energy tanks to do it, feel free to do the check anyways.**
  
That's pretty much all you should need to know rules-wise, so let's move on to the:

# Settings
- **death_link**: Enables death link. When you die, everyone else who has death link enabled also dies, and vice versa. A button will appear in the manual client next to the "connect" button in order to send deaths when you die. As mentioned above, a quick way to load the last checkpoint as if you died is through the minus button menu.
- **Metroidsanity**: Determines whether or not the Metroid Suit and Hyper Beam are randomized and needed to do the escape sequence (the escape being the only check they're required for).
    - Full Metroidsanity: both are randomized and needed to beat the game. Adds the checks "Raven Beak" and "Metroid Suit," both of which are checked by defeating Raven Beak.
    - Half: Only the Metroidsuit is randomized and needed to beat the game. Adds the check "Metroid Suit," which is checked by defeating Raven Beak.
    - Off: Neither item is randomized or needed to beat the game.
- **Omegasanity**: Determines whether or not the Omega Cannons are randomized. If this setting is enabled, you will need to get enough Progressive Omega Cannons before collecting an Omega Cannon and defeating the EMMI in its zone (the first Omega Cannon is needed to get the broken EMMI's Omega Cannon, the second is needed to get the second EMMI's Omega Cannon, etc. Essentially, this works the same way as the Progressive Key Items). Just like in game, the last EMMI does not need an Omega Cannon. Fair warning: this setting makes your Sphere 1 just 1 check, so be prepared to be BK'd at the start if you enable this setting.
- **Difficulty**: The difficulty mode you are playing the game in. Doesn't actually do anything randomizer-wise, but lets others see what mode you're playing the game in.

That's all the settings (for now), so that's all from me, unless you need help installing the apworld or Poptracker pack.

# Installation Instructions
Apworld: Double click the apworld to have it automatically install to the correct folder in Archipelago's files. 

Poptracker pack: Unzip the pack and move it to the "Packs" folder in Poptracker.

# Xeno Tactic Mod
This is a mod of the original "Xeno Tactic", a flash game made by Nowe Reginald in 2007.

I created this mod to fix a few bugs and add many Quality of Life features.

You can play this mod [here on GitHub](https://gabriele-ricciardi.github.io/xeno-tactic-mod/).

## Bug fixes

1. Plasma turret button: the button was unlocked at 25 gold, now it unlocks correctly at 15 gold.
2. InfoPanel.Cancel() would not set the "sell" button visibility to false. This created some corner cases sound bugs when using shortcuts (see QoL features).
3. Start/Pause/Resume button no longer makes sounds on press in Quit game overlay.
4. The End Game music did not stop when returning to Menu. Thus, when selecting Start from the Menu, the music would be heard twice. Now the music stops when accessing the Menu from the End Game frame.
5. Not exactly a bug, but the SAM turret icon was renamed to Missile Turret, as referred to in the game and the code.

## QoL features

1. Selling turrets at the start of the game gives back full gold. The correct amount is shown in the sell panel.
2. Shortcuts for most actions have been added to the game:
  - Place turret:
    - V - Vulkan turret
    - M - Missile turret
    - P - Plasma turret
    - D - DCA
    - S - Sonic Turret
    - W - Wall
  - Turret actions:
    - U - Upgrade
    - Del - Sell
  - Game actions:
    - Enter - Start/Pause/Resume game
    - Spacebar - Start/Send next wave
    - Q - Quit game overlay
3. Because of the shortcuts, it is now possible to select for placement and see the specifics of a turret before it is possible to buy it.
4. Because of 3, a new bug was introduced when placing a turret without the required amount of gold; its red block would not turn green when enough gold was available. This has been fixed by adding an additional check on the availability of the required gold each time a monster is slain. In this way, the red/green block is update automatically, without requiring a mouse move.

## Minor changes

1. In the main Menu, "More games" was changed to "Original", which opens a new tab with [the original Xeno Tactic uploaded to NewGrounds](https://www.newgrounds.com/portal/view/382321).
2. Changed main Menu background to include mod info.
3. All external links in the game were broken. These have been replaced with [Nowe Reginald's NewGrounds page](https://antebios.newgrounds.com/).

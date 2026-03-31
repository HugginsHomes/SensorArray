# Sensor Array

A World of Warcraft 1.12 (Vanilla) addon that lets you cycle through your known Find and Track spell abilities from a moveable on-screen button or a slash command.

---

## Features

- Cycles through all of your known tracking and finding abilities (Find Herbs, Find Minerals, Track Beasts, etc.)
- Small draggable button on screen for quick access
- Settings panel to choose which spells to include in the cycle
- Selected spells and button position are saved per character
- Slash command support for keybinding-friendly use

---

## Installation

1. Download or clone this repository.
2. Copy the `SensorArray` folder into your WoW addons directory:
   ```
   World of Warcraft\Interface\AddOns\SensorArray\
   ```
3. The folder should contain at minimum:
   - `SensorArray.lua`
   - `SensorArray.toc`
4. Launch WoW and enable the addon from the character select screen.

---

## Slash Commands

All commands work with either `/sa` or `/sensorarray`.

| Command | Description |
|---|---|
| `/sa` | Opens or closes the settings panel |
| `/sa next` | Cycles to the next selected tracking ability |
| `/sa hidebutton` | Hides the on-screen button |
| `/sa showbutton` | Shows the on-screen button |

---

## Settings Panel

Right-click the on-screen button or type `/sa` to open the settings panel.

- Check or uncheck spells to include or exclude them from the cycle.
- Only spells your character currently knows will be shown.
- Click **Save** to apply your changes. Click **Close** to dismiss without saving.

---

## Moving the Button

Hold **Alt** and drag the button to reposition it anywhere on your screen. Its position is automatically saved and restored the next time you log in.

---

## Supported Spells

### Profession / Racial
- Find Herbs
- Find Minerals
- Find Treasure
- Find Trees

### Hunter Tracking
- Track Beasts
- Track Demons
- Track Dragonkin
- Track Elementals
- Track Giants
- Track Hidden
- Track Humanoids
- Track Undead

---

## Saved Variables

Settings are stored per character in:
```
WTF\Account\<AccountName>\<Realm>\<CharacterName>\SavedVariables\SensorArray.lua
```

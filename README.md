# MRWHITEE_R CS:GO Configs

> Complete CS:GO configuration package for competitive play, training, and warmup. Includes optimized game settings, keybinds, server configs, and custom scripts for enhanced gameplay and practice.

---

## Table of Contents

1. [Overview](#overview)
2. [Included Scripts](#included-scripts)
3. [Key Features](#key-features)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Visual Keybinds (Optional)](#visual-keybinds-optional)
7. [Credits](#credits)

---

## Overview

MRWHITEE_R Configs are designed for:

* Smooth, competitive gameplay.
* Optimized graphics, HUD, radar, and sound.
* Full keybinding setup for quick actions, weapon selection, and custom commands.
* Server configurations for LAN, competitive, and practice matches.
* Warmup and training scripts for aiming, movement, and grenade practice.

All configs are modular, allowing you to **load everything automatically via `autoexec.cfg`**.

---

## Included Scripts

| Category               | File / Script             | Purpose                                                                |
| ---------------------- | ------------------------- | ---------------------------------------------------------------------- |
| **Commands Shortcuts** | `commands_shortcuts.vcfg` | Weapon / map shortcuts, utility aliases                                |
| **Game Settings**      | `gamesettings.vcfg`       | Graphics, HUD, radar, crosshair, sound, mouse                          |
| **Keybinds / Binds**   | `key_binds.vcfg`          | Movement, weapon selection, mouse actions, custom binds, function keys |
| **Server Config**      | `lan.vcfg`                | Economy, rounds, friendly fire, bots, overtime, pause/unpause          |
| **Warmup / Training**  | `warmup.vcfg`             | Infinite ammo, bunnyhop, movement optimization, slow-motion training   |

---

## Key Features

### Commands Shortcuts

* Quick buy / give weapons (`g_m4`, `b_ak47`)
* Map shortcuts (`mirage`, `dust2`, `nuke`)
* Shield equip and local server utilities (max health, debug)

### Game Settings

* **Graphics:** Brightness, player contrast, unlimited FPS
* **HUD:** Player count, scoreboard cursor, clan info toggle
* **Radar:** Scale, rotate, center, icon size
* **Sound:** Volume control, voice chat, EQ profiles, MVP cues
* **Mouse:** Sensitivity, yaw/pitch, zoom ratios

### Keybinds

* **Movement:** WASD, jump, crouch, sprint
* **Weapon Selection:** Number keys, scroll wheel for grenades/jump
* **Mouse:** Shoot, scope, push-to-talk, ping, custom text messages
* **Interaction:** Reload, use, graffiti, radio commands
* **Custom:** Wallhack toggle, crosshair color/bold, quick weapon switch
* **Function Keys:** Pause/unpause, game volume toggle, personal config loader

### Server Config

* **Economy:** Kill rewards, bomb/hostage interaction, start money
* **Damage:** Friendly fire, bullet/grenade reductions
* **Rounds:** Round time, max rounds, freeze time, warmup
* **Bots:** Behavior, quota, freeze, knife-only mode
* **Overtime:** Enable, max rounds, start money

### Warmup / Training

* Cheats enabled (`sv_cheats 1`) for practice
* Infinite ammo, grenade reset/removal
* Fast respawn and unlimited money
* Bunnyhop, movement optimization, max velocity
* Slow-motion aiming drills via `host_timescale`

---

## Installation

1. Place all `.cfg` files into your CS:GO `cfg` folder:

```text
C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg
```

2. Create or update `autoexec.cfg` to automatically load all scripts:

```cfg
exec commands_shortcuts.vcfg
exec gamesettings.vcfg
exec key_binds.vcfg
exec lan.vcfg
exec warmup.vcfg
```

3. Ensure **Developer Console** is enabled in CS:GO settings.
4. Launch CS:GO — all scripts will load automatically.

---

## Usage

* **Competitive Play:** Use the main scripts (`commands_shortcuts`, `gamesettings`, `key_binds`, `lan`) for optimized gameplay.
* **Warmup / Training:** Use `warmup.vcfg` to practice movement, grenades, aiming, and wallbang setups.
* **Server Control:** Pause/unpause matches with the bound keys (`"` by default).

---

## Visual Keybinds (Optional)

For easier onboarding, a **visual diagram of all custom keybinds and actions** can be included. It shows keys like movement, grenades, push-to-talk, crosshair, and custom messages at a glance.

*(Add diagram here if available)*

---

## Credits

* Configs created & modified by **MrWhiteE_R**
* Inspired by competitive CS:GO gameplay standards and training routines

---

✅ **All configs are modular. Simply run `autoexec.cfg` and enjoy full setup!**


---

### Visual Keybinds Overview

| Category                  | Key / Button                          | Action                                      |
| ------------------------- | ------------------------------------- | ------------------------------------------- |
| **Movement**              | W / S / A / D                         | Move Forward / Backward / Left / Right      |
|                           | LEFT SHIFT                            | Walk / Silent Sprint                        |
|                           | SPACE                                 | Jump                                        |
|                           | LEFT CTRL                             | Crouch                                      |
| **Weapon Selection**      | 1 / 2 / 3 / 4 / 5 / 6 / 7 / 8 / 9 / 0 | Primary / Secondary / Knife / Grenades / C4 |
| **Mouse**                 | MOUSE1                                | Shoot / Place Pack                          |
|                           | MOUSE2                                | Scope                                       |
|                           | MOUSE3                                | Custom text / Noclip                        |
|                           | MOUSE4                                | Ping / Bot Place                            |
|                           | MOUSE5                                | Voice Chat / Retrow Grenade                 |
|                           | SCROLL UP                             | Flashbang / Knife                           |
|                           | SCROLL DOWN                           | Jump                                        |
| **Interaction / Utility** | E                                     | Use / Interact / Disarm                     |
|                           | R                                     | Reload Weapon                               |
|                           | T                                     | Graffiti Menu                               |
|                           | Y                                     | Message All                                 |
|                           | U                                     | Message Team                                |
|                           | G                                     | Drop Weapon                                 |
|                           | Z                                     | Radio Wheel                                 |
|                           | C / ,                                 | Basic Radio                                 |
|                           | B                                     | Buy Menu                                    |
|                           | M                                     | Team Menu                                   |
|                           | F1                                    | Autobuy                                     |
|                           | F2                                    | Rebuy                                       |
| **Custom / Advanced**     | \                                     | Wallhack Toggle                             |
|                           | /                                     | Console Toggle                              |
|                           | `                                     | Buy First Gear                              |
|                           | ARROW UP / DOWN                       | Mic Volume Up / Down                        |
|                           | END                                   | Disconnect Troll                            |
|                           | ENTER                                 | Slam Music / Push-to-Talk                   |
|                           | INS                                   | Show Teammates / Loadout                    |
|                           | NUMPAD DEL / ENTER / INS              | Custom Messages                             |
|                           | NUMPAD - / +                          | Buy / Give Grenades / All Weapons           |
|                           | PGUP / PGDN                           | Crosshair Bold / Color                      |
|                           | Q                                     | Quick Weapon Switch                         |
|                           | RIGHT ALT                             | Mute / Unmute Players                       |
|                           | TAB                                   | Show Score / FPS / Ping                     |
|                           | BACKSPACE                             | Sell Items                                  |
|                           | F                                     | Inspect Weapon                              |
|                           | V                                     | Weapon Preview                              |
| **Function Keys**         | F4                                    | Random Text                                 |
|                           | F7                                    | Mic Test                                    |
|                           | F9                                    | Toggle Game Volume                          |
|                           | F10 / F11 / F12                       | LAN / Personal Config / Mode                |
|                           | ESC                                   | Cancel / Exit Menu                          |
|                           | F1 / F2                               | Autobuy / Rebuy                             |

---

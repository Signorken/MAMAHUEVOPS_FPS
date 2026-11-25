# MAMAHUEVOPS

Fast arena FPS in the spirit of early-2000s console shooters. Bots, online play, full gamepad support and local split-screen for up to 4 players.

**Platforms:** Windows · Linux · macOS (Apple Silicon + Intel)

## Download

Get the latest ZIP for your system from the [Releases](../../releases/latest) page, unzip and run.

- **Windows:** run `MAMAHUEVOPS.exe`
- **Linux:** `chmod +x MAMAHUEVOPS.x86_64`, then run it
- **macOS:** right-click the app → Open on first launch (the app is not notarized)

The game checks for updates by itself (main menu → *Check for updates*). On Windows and Linux only the game data is downloaded.

## Highlights

- **Full gamepad support**: Xbox / PlayStation icons, weapon wheel, adjustable look speed, turn acceleration and dead zone, aim assist (Low / Standard), full rebinding.
- **Local split-screen, 2–4 players**: any mix of gamepads, plus one keyboard + mouse. Each player picks a colour and joins in their own quadrant.
- **Online**: host or join with direct IP, LAN or the server browser; up to 8 players, bots fill the rest.
- **Bots** with three difficulty levels, used in every mode.
- 5 maps, 8 weapons, 4 powerups.

## Game modes

| Mode | Rules |
|---|---|
| **Deathmatch** | Free for all. First to N kills. |
| **Team Deathmatch** | Blue vs Red. First team to N kills. |
| **Capture the Flag** | Take the enemy flag to your base while yours is at home. Dropped flags return after 15 s. |
| **King of the Hill** | Hold the glowing hill alone to score. The hill moves every 60 s on larger maps. |
| **Gun Game** | Everyone climbs the same weapon ladder, 2 kills per weapon, finishing with the Knife. A melee kill sends the victim one level back. |
| **Last Man Standing** | Fixed number of lives, the last survivor wins. |

Kill, score and time limits are configurable; every limit can be turned off.

## Weapons

Each weapon has a primary and an alternate fire.

| Weapon | Primary | Alt |
|---|---|---|
| Knife | Fast stab, always available, faster movement | Slow stab, instant kill |
| Pistol | Accurate single shots | 3-round burst |
| Shotgun | One barrel | Both barrels |
| Submachine Gun | 3-round bursts | Switch to full auto |
| Assault Rifle | Slow, hard-hitting, accurate at any range | Grenade |
| Plasma Gun | Rapid plasma bolts, overheats | Plasma orb with splash |
| Rocket Launcher | Rocket | Salvo of 3 |
| Railgun | One-shot kill through everyone in line, then overheats | Zoom |

A melee strike is available with any weapon. Only the Railgun can zoom.

## Powerups

- **Double Damage**: ×2 damage.
- **Invisibility**: nearly invisible.
- **Shield**: takes 25% of the damage.
- **Speed**: much faster.

Health and armor go up to 200 (megas).

## Maps

Bunker · Campgrounds · Foundry · Open Field · Shipment

Capture the Flag is available on Foundry and Shipment.

## Controls

| Action | Keyboard + mouse | Gamepad |
|---|---|---|
| Move / Look | WASD / Mouse | Left stick / Right stick |
| Fire / Alt fire | Left / Right mouse | RT / LT |
| Jump / Crouch | Space / Ctrl | A / B |
| Reload | R | X |
| Weapons | Wheel, Q / E, 1–8 | Hold LB: weapon wheel · RB: next · Y: knife |
| Melee | F | L3 |
| Scoreboard / Pause | Tab / Esc | Back / Start |

Everything can be rebound in *Options → Controls*.

## Split-screen

Main menu → **Play** → **Split screen**. Choose 2, 3 or 4 players, then each player presses **A** on their gamepad (or **Enter** for keyboard + mouse) to join. Player 1 starts the match.

## Graphics

Three presets: **Performance** (light renderer, for old CPUs and integrated GPUs), **Balanced** and **Quality**. FPS cap up to 300, optional VSync, adjustable field of view. A built-in **Benchmark** (main menu) measures your average and 1% low FPS.

## Online

Main menu → **Online**. The host needs UDP ports 7777–7778 open (UPnP is available in the game), or everybody can use a VPN such as ZeroTier, Radmin VPN or Tailscale. Everyone must run the same game version.

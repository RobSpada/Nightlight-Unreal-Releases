# Nightlight

An online multiplayer top-down space game: Newtonian flight, ships you can walk around inside, a station to dock at,
jobs to take, pirates to fight. This repository holds the **downloadable builds** only.

**Early test build.** Expect rough edges.

## Download and install (Windows)

1. Download **Nightlight-Setup.exe** from the [latest release](https://github.com/RobSpada/Nightlight-Unreal-Releases/releases/latest)
   (about 20 MB) and run it. It installs the **Nightlight launcher** (no administrator rights needed; Windows asks only
   if the Visual C++ runtime is missing, or if you tick "allow hosting").
2. The launcher downloads the game the first time (about 1.1 GB) and then starts it with **PLAY**.

**Updates are automatic:** every time you open the launcher it checks for a new version and downloads only the parts
of the game that changed, never the whole game again. **REPAIR** re-checks every file if something goes wrong.
(The many `.bin` files in each release are those parts; you never need to download them yourself.)

To remove it: *Settings > Apps > Nightlight > Uninstall*.

**You need:** Windows 10 or 11 (64-bit), a DirectX 12 graphics card (an NVIDIA RTX card is recommended; the game uses
Lumen lighting and DLSS), about 8 GB of free disk space.

## Playing together

From the main menu:

- **Host a game**: your friends join you. On the same network they type the address the menu shows. Over the
  internet, forward **UDP port 7777** on your router to your PC and give them your public address.
- **Join a game**: type the host's address.

In game: **Enter** chat, **P** the pilots list (invite to your party, offer credits, hand over your helm), **Y / N**
answer requests. Party members walk aboard your ship freely; anyone else asks first.

## Controls (the basics)

| | On foot | Flying |
|---|---|---|
| Move | W A S D | W thrust, S brake, A / D turn, E / Q strafe |
| Use / take a seat | E / F | F leave the seat |
| Star map and jump | | M map, Up / Down choose, Enter jump, J cancel |
| Weapons | | Left mouse guns, right mouse missiles |
| Dock | | C at a station port (or at Kessler Relay's airlock) |
| Power and shields | | 1 weapons, 2 shields, 3 engines, 4 life support, 5 even; 6-9 shield facing |

Jobs are on the board in Elyse Station's management office.

# Nightlight

An online multiplayer top-down space game: Newtonian flight, ships you can walk around inside, a station to dock at,
jobs to take, pirates to fight. This repository holds the **downloadable builds** only.

**Early test build.** Expect rough edges.

## Download and install (Windows)

1. Open the [latest release](https://github.com/RobSpada/Nightlight-Unreal-Releases/releases/latest).
2. Download **every** file of the release into one folder: `Nightlight-<version>-Setup.exe` and the `.bin` parts
   beside it (the installer is split to fit GitHub's file size limit).
3. Run `Nightlight-<version>-Setup.exe` and follow the steps. It installs the Unreal runtime it needs, adds Start-menu
   and desktop shortcuts, and (if you tick it) opens UDP port 7777 in the Windows firewall so you can host games.

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
| Dock | | C at a station port |

Jobs are on the board in Elyse Station's management office.

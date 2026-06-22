# Back Teleport Skript

A lightweight and configurable Minecraft Skript that allows players to return to their previous death location using `/back`.

This Skript is useful for survival, lifesteal, skyblock, factions, and other Minecraft servers where players need a simple way to return after dying.

---

## Features

* Return to your previous location using `/back`
* 3-second teleport countdown
* Action bar countdown message
* Movement cancels the teleport
* Back location automatically expires after 5 minutes
* Cleans saved data when a player disconnects
* Fully configurable teleport delay and expiry time
* Lightweight and easy to install

---

## Dependencies

* Minecraft server with Skript support
* Skript 2.9 or newer

---

## Commands

| Command | Description                                           |
| ------- | ----------------------------------------------------- |
| `/back` | Teleports the player to their saved previous location |

---

## Permissions

| Permission | Description                      |
| ---------- | -------------------------------- |
| `back.use` | Allows the player to use `/back` |

---

## Installation

1. Download the Skript file.
2. Place the file inside your server folder:

```text
/plugins/Skript/scripts/
```

3. Restart your server or run:

```text
/sk reload back
```

4. Give players the permission:

```text
back.use
```

---

## How It Works

When a player dies, their location is saved for a limited time.

After respawning, the player can use:

```text
/back
```

The Skript starts a short countdown before teleporting the player. If the player moves during the countdown, the teleport is cancelled.

The saved location expires automatically after 5 minutes.

---

## Recommended For

* Survival servers
* Lifesteal servers
* Skyblock servers
* Factions servers
* Hardcore-style servers
* SMP servers

---

## Support

For support, bug reports, or suggestions, contact the resource author through BuiltByBit or https://github.com/hiteshmalhotra2026/-back-skript/issues

---

## Author

Created by **HACK Studio**
Author: **itzz_hitesh**

---

## License

This resource is protected by copyright.

You are not allowed to resell, redistribute, or claim this Skript as your own without permission.

# CJH Skript Snippets

A collection of Skript scripts by CJH (and friends). These used to be sold on my Discord server and are now free for everyone. Join [CJH's support Discord](https://discord.gg/5Dr4XR5Znj) for help.

**Free to use, not free to resell or redistribute.** See [LICENSE.md](LICENSE.md).

## Setup

1. Download the scripts you want from the [scripts/](scripts/) folder.
2. Most scripts need `CJHUtils.sk` (listed under Requires in their header). Install it first and make sure it loads before the others.
3. Drop the files into `/plugins/Skript/scripts/`.
4. Check the header of each file for required addons (SkBee, skript-reflect, skript-gui, etc.).
5. Run `/sk reload scripts`.

Every script has a header comment with a description, requirements, and configurable values near the top.

## Scripts

| Script | Description | Requires |
|---|---|---|
| [CJHUtils.sk](scripts/CJHUtils.sk) | Shared utility functions used by most scripts here. **Install this first.** | Skript, SkBee |
| [AuctionHouse.sk](scripts/AuctionHouse.sk) | GUI auction house with listings, pagination, and confirmation menus | SkBee, skript-gui |
| [Chat.sk](scripts/Chat.sk) | Better chat event with mentions, replies, hex colors, and `[item]` placeholders | SkBee, skript-reflect |
| [Chatcolors.sk](scripts/Chatcolors.sk) | Chat color selector with GUI and dialog support, 60+ colors unlocked by permission | SkBee, SkNMS, skript-gui, skript-reflect |
| [Combat.sk](scripts/Combat.sk) | Combat log and `/pvp` toggle | SkBee |
| [Economy.sk](scripts/Economy.sk) | Balance, pay, withdraw to bank notes, and admin commands | SkBee, skript-reflect |
| [Guilds.sk](scripts/Guilds.sk) | Team/clan system with ranks, invites, team chat, and management commands | SkBee |
| [LuckpermsAPI.sk](scripts/LuckpermsAPI.sk) | PermSK replacement with custom LuckPerms expressions | skript-reflect, LuckPerms |
| [Mining.sk](scripts/Mining.sk) | Custom mining with ore health and regeneration | SkBee, skript-reflect, oopsk |
| [Punishments.sk](scripts/Punishments.sk) | GUI punishment system with warns, mutes, bans, and automatic escalation | SkBee, skript-gui |
| [Scoreboard.sk](scripts/Scoreboard.sk) | Customizable scoreboard with per-player settings GUI | SkBee, skript-gui, skript-placeholder |
| [Shop.sk](scripts/Shop.sk) | SMP/Lifesteal style shop with 100+ configurable items | SkBee, skript-gui, skript-reflect, oopsk |
| [Signatures.sk](scripts/Signatures.sk) | Sign items with a custom signature | SkBee |
| [StaffChat.sk](scripts/StaffChat.sk) | Staff chat with `/sc` and toggle (by Fusezion) | SkBee |
| [Trash.sk](scripts/Trash.sk) | `/trash` GUI for deleting items | SkBee, skript-gui |
| [chucknorris.sk](scripts/chucknorris.sk) | Chuck Norris jokes from an API, with sign support | skript-reflect |
| [_AtlasSprites.sk](scripts/_AtlasSprites.sk) | Send atlas sprites (item, GUI, painting icons) as chat components | SkBee, skript-reflect (Skript 2.14.3 or lower) |
| [_LibsDisguisesAPI.sk](scripts/_LibsDisguisesAPI.sk) | Functions for the LibsDisguises API (disguise, undisguise, check) (by wrexbg) | skript-reflect, LibsDisguises |

## Support

Bugs, questions, and requests go in [CJH's support Discord](https://discord.gg/5Dr4XR5Znj). No guaranteed support, but I will help when I can.

## License

Free to use and modify on your own servers. Do not resell or redistribute. Full terms in [LICENSE.md](LICENSE.md).

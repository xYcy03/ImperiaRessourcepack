# Imperia SMP Resource Pack

Minecraft Java 26.1 resource pack for Imperia TAB, rank emblems, and SMP quest/shop/cosmetic UI glyphs.

## Glyph mapping

- `U+E000`, `U+E00F`, `U+E010`: legacy segmented Imperia banner glyphs (retained for compatibility)
- `U+E026`: full IMPERIA wordmark, scaled to match the former TAB and scoreboard banner footprint
- `U+E001`–`U+E00E`: Owner, Manager, Developer, Admin, Moderator, Supporter, Builder, Helfer, Peria, Monarch, Titan, Apex, Guardian, Spieler rank emblems
- `U+E011`–`U+E013`, `U+E019`–`U+E01D`: Money, Coins, Piñata, Level, Clan, Playtime, Claim, Player scoreboard icons
- `U+E01E`–`U+E025`: MONEY, COINS, LEVEL, PINATA, CLAN, TIME, CLAIM, PLAYER bitmap scoreboard badges
- `U+E014`–`U+E018`: Questbook, Coinshop, Cosmetics, Companion/Plushie, Custom Enchants
- `U+E027`–`U+E029`: Daily rewards, Bank overview, Command handbook
- `U+E02A`–`U+E031`: Beta, Supporter, Discord, Valentine, Easter, Halloween, Winter, Custom badge

The font definition includes Minecraft's vanilla fallback providers. The resource pack remains optional on the server.

The v1.10 banner is about 20% smaller, the three word segments join more tightly, and rank emblems render at half their former size.

The v1.11 scoreboard atlas contains compact transparent pixel icons. Money uses green, Coins a simple gold coin, and the piñata is a right-facing colorful llama.

The v1.12 scoreboard adds compact bitmap text badges with a shared amethyst frame and a distinct jewel-tone accent per category.

The v1.13 scoreboard badges use cleaner 4x7 small-cap pixel lettering in soft gray, while each category keeps its distinct accent color.

The v1.14 pack uses the new transparent IMPERIA wordmark in both TAB header and SunLight scoreboard title.

The v1.15 pack adds three navigation glyphs for Daily, Bank, and the command handbook, plus eight original purple-fantasy badge glyphs for selectable TAB/nametag badges.


## Server RP glyphs (26.1.2)

This pack is compatible with Minecraft Java 26.1.x (Paper server resource packs are client-side). Custom glyphs can be placed in TAB prefixes or menu item names using these characters:

### Rank images

| Glyph | Rank image |
|---|---|
| `\uE032` | Dev |
| `\uE033` | Guardian |
| `\uE034` | Helfer |
| `\uE035` | Monarch |
| `\uE036` | Peria |
| `\uE037` | Spieler |
| `\uE038` | Support |
| `\uE039` | Titan |

### Menu action glyphs

| Glyph | Icon |
|---|---|
| `\uE03A` | Close (X) |
| `\uE03B` | Back |
| `\uE03C` | Next |
| `\uE03D` | RTP |
| `\uE03E` | Home |
| `\uE03F` | Shop |
| `\uE040` | Info |
| `\uE041` | Confirm |

Use the actual private-use characters (copy/paste the corresponding glyph from a character map or generate it in your config editor); the `\uE0xx` strings above document the codepoints. Menu glyphs only render icons. Click actions and inventory layouts must be configured by the server's menu plugin/Core.

### GUI frame glyphs

| Slots | Glyph |
|---:|---|
| 9 | `\uE050` |
| 18 | `\uE051` |
| 27 | `\uE052` |
| 36 | `\uE053` |
| 45 | `\uE054` |
| 54 | `\uE055` |

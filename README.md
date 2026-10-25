# Easylife

Small quality-of-life helpers for **World of Warcraft Retail (Midnight, 12.x)**, in one addon:
protect your valuable items, let merchants sell your junk, see what your farming is worth, and keep
notes on the map, on items and on people. Every part is a module you can switch on or off.

English and German game clients are fully supported.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J0V829H58P)

## Getting started

- **Easylife window:** left-click the minimap button (or the entry in the addon menu next to the
  minimap), or type `/el`. It opens on the **Overview**: all keys - set them right there -, the status of
  the account sync, and every module with its settings.
- **Settings:** right-click the minimap button, or `/el config`. Every page explains itself; hover any
  option for details.
- **The item menu:** hover over an item and press the item menu key, or **Alt+right-click** it in your
  bags, bank or Baganator. One menu for everything Easylife can do with it: lock, mark for sale, always
  sell, track for farming, write a note. A normal right-click still uses the item as usual.
- **Undo:** deleting something (a note, a farm session, a rule ...) shows an "Undo" bar for a few seconds.
- `/el help` lists all chat commands.

## What it does

### Item Lock - never lose an item again

- Lock single items (default key **CTRL-H**) or every item of a kind - for this character, this account
  or all your accounts. Items of your equipment sets can be protected automatically.
- Locked items are protected against selling (an accidental sale is bought back right away), destroying,
  scrapping, disenchanting, the auction house, mail and trade - each with its own setting and per-item
  exceptions.
- A lock icon in your bags, bank, Baganator and the character window; a warning when you take a locked
  item off.
- The **Item Lock** tab lists the locked items of all your characters, with where they are.

### Merchant - selling and repairing done for you

- Sells grey items automatically when you open a merchant; optionally low-level food and toys you
  already know. Hold **Shift** while opening the merchant to skip it once.
- Mark items for sale (default key **CTRL-J**) or set them to **always sell** - for one character, the
  whole account or all accounts. A coin in your bags shows what will be sold.
- Never sells more than the buyback list holds (12), so everything can be bought back.
- Repairs automatically, with guild gold first if you are allowed to.

### Farming - what is your farming worth?

- Track the items you farm (default key **CTRL-F**): the **farm view** shows how many you gather per hour
  and the gold per hour, with prices from Auctionator, TradeSkillMaster or the merchant.
- Sessions start and pause by themselves, count raw gold and merchant income, and list all other loot.
- Goals per item and per session, item sets to switch what you track, a bag space warning.
- A **questing view**: quest gold, quests and XP per hour, time to the next level, and what became of
  your quest rewards.
- The **history** of your sessions, the **best spots** per zone and **gathering points** on the world map.

### Notes - remember everything

- **Map pins** with a comment: Alt+click on the world map, or pin where you stand. Kinds for vendors,
  treasures, rares and to-dos, done marks, respawn timers, pins on the minimap, and reminders when you
  come close.
- **Item notes** (default key **CTRL-N**), shown in the tooltip, at the auction house and as a warning
  when you sell the item.
- **Where did I get this?** Every merchant purchase, loot and quest reward is remembered with the place.
- Notes on **players and NPCs**, shown in their tooltip.
- Import and export `/way` lines (TomTom format, e.g. from Wowhead).

### Multiboxing

- Accepts group invites and shared quests from your own characters automatically - and summons, if you
  switch that on.

### Your other WoW accounts

If you play two WoW accounts of the same Battle.net account at the same time, **account sync** shares
locked items, sell rules, notes, pins and farming data between them (read-only on the other side). You
confirm each account once.

## Works with

- **Baganator** (icons and Alt+right-click in its bags; with Syndicator, item counts of all characters)
- **TomTom** (waypoints), **Auctionator** and **TradeSkillMaster** (prices)
- Addons that do the same job (e.g. other auto-sell or repair addons) are detected after login, and
  Easylife offers to switch them off so nothing happens twice.

## Commands

| Command | What it does |
|---|---|
| `/el` | open / close the Easylife window |
| `/el config` | open the settings |
| `/el list` · `/el sell` · `/el notes` | open the Item Lock, Merchant or Notes tab |
| `/el farm` | show / hide the farm view (`/el farm reset` starts a new session) |
| `/el pin [comment]` | pin your position on the map |
| `/el way <line>` · `/el way export` | import a `/way` line · show your pins as `/way` lines |
| `/el charnote [Name]` | note on your character (or another one) |
| `/el unmark` | remove all sale marks |
| `/el sync` | account sync status, sync now |
| `/el addons` | check for overlapping addons |
| `/el changelog` | what's new |
| `/el help` | all commands |

## Download

Get the latest version from the [Releases](https://github.com/dmm1/easylife-addon/releases) page and unpack
the `Easylife` folder into `World of Warcraft\_retail_\Interface\AddOns`.

## More

- What changed in each version: [CHANGELOG.md](CHANGELOG.md) (English), [CHANGELOG.de.md](CHANGELOG.de.md)
  (German) - also in game in the "What's new" tab.
- License: [MIT](LICENSE).

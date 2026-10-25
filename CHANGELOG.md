# Changelog

All notable changes to Easylife. The German version is in `CHANGELOG.de.md`;
both are shown in game under "What's new". New entries go under "Unreleased".

## Unreleased

## 1.13.1 - 2026-10-20

### Easier to use
- **Alt+right-click on an item** in your bags, the bank or Baganator opens the Easylife menu (lock, mark for sale, always sell - for this character, this account or all accounts -, track, note). A plain right-click still uses the item. The item tooltip names the click; both can be switched off on the main settings page.

## 1.13.0 - 2026-10-20

### Easier to use
- **Item menu key:** one key for everything - hover over an item and press it: a menu offers lock, mark for sale, track for farming and note, whatever your enabled modules can do with it. Set it in the new "Overview" tab (or the game's key bindings); the single keys stay.
- **"Overview" tab:** the first tab of the Easylife window lists all keys with "Set key" right there, the account sync status, minimap button and chat messages, and every module with its settings (or "Turn on").
- **`/el` opens the Easylife window** (like the minimap button); `/el config` opens the settings.
- **Resizable window:** drag the grip at the bottom right; the size is kept. The window is a bit wider by default.
- **Right-click menus in the tabs:** rows in "Item Lock", "Merchant", "Farming" and "Notes" have the same actions on right-click (options, scope, edit, map, delete ...). Remove, delete and map buttons are small icons now, so names get more room.
- **Undo:** deleting a farm session, a note or pin, an "always sell" or lock rule, or clearing gathering points shows an "Undo" bar for 10 seconds.
- **Chat messages:** new setting "Important only" (main page or Overview) leaves out confirmations like "locked" or "tracked"; warnings and results always show. The item flashes briefly when a key worked.
- **Reload right away:** switching a module or the account sync on or off offers "Reload now" instead of a chat line.
- **Settings:** options that only matter with another one on (e.g. "Levels below your character" under "Sell low-level food and drink") are indented and greyed out while it's off. The hint texts are shorter; details moved into the tooltips. Closing the settings opened from the gear brings the Easylife window back.
- **Key binding:** a key that is already used needs a second press before it is replaced.
- Tabs and modules are named alike: "Item Lock" and "Merchant" tabs, module "Notes".

### Farming
- Marked farming items are now called **tracked** items everywhere (key, tab, farm view, item sets), so they don't mix up with items marked for sale.
- **Farm view:** a gear button in the title opens item sets, session goals and the chat summary (also still on right-click); the minus button collapses it to one line with the gold per hour. "Restart" asks first once a session has something to lose. Longer item names fit.

### Fixed
- The minimap button hint in the settings listed the wrong tabs.
- The "Notes" tab cut off its summary line in German; it now leaves out empty groups (hover shows it in full).

## 1.12.1 - 2026-10-20

### Farming
- **Shared with your other accounts:** with account sync on, your history (and with it the best spots), gathering points and item sets also reach your other WoW accounts - read-only and marked with the account: history rows without "Delete", their sessions count in the best spots, their gathering points show on the map, their item sets can be loaded from the item set menu. Gathering points are sent when a session ends. Setting: "Share farming data with my other accounts". (All characters of one WoW account share this data anyway.)

## 1.12.0 - 2026-10-20

### Farming
- **Gathering points on the world map:** every gain of a marked item remembers where you were; the map shows small item icons there (setting "Show gathering points on the world map"). Right-click a row in the farm view to open the map there or to clear the points.
- **Best spots:** the "Farming" tab compares your farming zones from the history - gold per hour on average, number of sessions, the best one with a waypoint to where it started.
- **Session goals:** right-click the farm view's title -> gold or time for every session (e.g. 10,000 g or 60 minutes); progress at the bottom of the farm view and a notice when it's reached.
- **Post the summary in chat:** the same menu sends zone, time, gold (per hour) and your best items to your group, guild or say.

### Notes & locations
- **Notes on players, NPCs and your characters:** hover over a player or NPC (or target it) and press the note key; the note shows in their tooltip. NPC notes count for every copy of that NPC. Your own characters: "New note ..." in the "Notes" tab or `/el charnote [Name]`. New group "Players and NPCs" in the tab.
- **Respawn timer on pins:** give a rare or treasure pin a respawn time in its window, Ctrl-click it on the map when you killed or looted it - the pin turns red and you get a notice when it's up again (also after a relog).
- **Note at the auction house:** an item with a note in the auction house's sell slot shows its note in a small panel next to the window.

## 1.11.4 - 2026-10-20

### Farming
- Fixed: the session clock in the farm view sometimes jumped by 2 seconds (and showed other seconds twice); it now counts every second.

## 1.11.3 - 2026-10-20

### Farming
- **Note from the farm view:** right-click a row (farming and questing view) -> "Add note ..." / "Edit note ..." opens the note window of the Notes module for that item.
- Fixed: when you stopped tracking an item, what you had farmed of it this session disappeared instead of going back to "Other loot".

### Notes & locations
- **Where looted items come from:** items from loot and quest rewards (rare and better, adjustable) are remembered with zone, coordinates, date and the name of the dead creature you had targeted or the quest - in the tooltip ("Looted: ..." / "Quest reward: ...") and in the new "Loot and quests" group of the "Notes" tab.
- **Reminders:** entering a zone with pins tells you in chat how many there are; coming close to a to-do, rare or treasure pin shows its comment on screen (distance adjustable, once per 15 minutes).
- **Pins on the minimap** (hover: comment, click: waypoint; turns with a rotating minimap).
- **Done:** Shift-click a pin on the world map (or tick "Done" in its window) - it fades on the maps and gives no more reminders; "Hide done pins" removes them from the maps.
- **Export as /way lines:** "/way ..." in the "Notes" tab (or `/el way export`) shows all pins or those of your zone as /way lines to copy for friends or your guild.

## 1.11.2 - 2026-10-20

### Notes & locations
- **Warning when you sell an item with a note:** a message in the middle of the screen, the note in chat and a window to buy it back - selling is never blocked. Choose for which items in the settings: not bound (on by default, also bind on equip and "warbound until equipped"), soulbound, warbound. Items you marked for sale or set to "always sell" give no warning.

## 1.11.1 - 2026-10-20

### Notes & locations
- **Shared with your other accounts:** with account sync on, pins, item notes and purchases of your other WoW account show here too - on the map, in tooltips and in the "Notes" tab, read-only and marked with that account. Settings: "Share my notes with my other accounts".
- **Pins on continent and world maps:** zone pins also appear (a bit smaller) when the map shows the continent or the world (can be switched off).
- **Import /way lines** (TomTom format, e.g. from Wowhead): "Import /way" in the "Notes" tab or `/el way` - paste one or many lines; zone names, `#mapID` and decimal commas are understood, existing pins are skipped.
- **Note icon in the bags:** items with a note show a small note in the top right corner (default bags, bank, Baganator); the sale coin takes priority.

## 1.11.0 - 2026-10-20

### Notes & locations (new module)
- **Map pins with comments:** Alt+click on the world map places a pin there - pick a kind (note, vendor, treasure, rare, to do) and write a comment. Hover a pin for its comment, left-click for a waypoint, right-click to edit or delete. "Pin my position" (or `/el pin`) pins where you stand.
- **Item notes:** hover an item and press the note key (default `CTRL-N`), or drag an item onto "Item note" in the "Notes" tab. A note counts for the item kind, can save your current location, and shows in the item's tooltip. Items with a note are no longer sold automatically as junk, old food or known toy (marked items still are).
- **Purchases are remembered:** every item bought from a merchant is saved with merchant, zone, coordinates, date and price, and shows in its tooltip - months later you still know where it came from.
- **"Notes" tab** in the Easylife window (`/el notes`): pins, item notes and purchases, searchable by comment, zone, item or merchant, with a "This zone" filter; "Map" opens the place on the world map.

## 1.10.7 - 2026-10-19

### Farming
- **Quest rewards in the "Farming" tab:** their own group with what became of each one (in your bags, sold, equipped, used up); they are no longer listed again under other loot there. In the questing view the tab's summary line shows quests, quest gold and XP per hour.
- **Chat summary** after Restart now also lists quests, quest gold, sold rewards and XP of questing sessions.

## 1.10.6 - 2026-10-19

### Farming
- **Questing / Farming button** at the bottom right of the farm view switches between the two views (replaces the small icon next to the title).
- Fixed: the session clock in the farm view could stand still while "running" (until something was looted) - also after Pause and Start.
- Fixed: XP could be counted wrong right after logging in when the game hadn't loaded the XP yet.

## 1.10.5 - 2026-10-19

### Farming
- **Questing view:** click the small icon next to the farm view's title to switch (each character remembers its view). It shows quest gold, sold quest rewards, raw gold and other merchant income, quests per hour and - below the maximum level - XP per hour and the time to the next level. In this view quest gold counts towards the total per hour; with "Start automatically", turning in a quest starts a session.
- **Quest rewards:** items you get from quests are recognised and listed in the questing view with what became of them - sold (coin), equipped (check mark), used up or sent away (grey) or still in your bags; buying back undoes a sale. In the farming view they are marked in "Other loot".
- Fixed: gear you take off no longer shows up in "Other loot".
- Quest objective items no longer show up in "Other loot". The history also keeps quests, quest gold, sold rewards and XP.
- **Waypoint** button in the history: leads back to where a session started - TomTom's arrow if installed, else Blizzard's map pin with navigation. Sessions that started inside an instance have no coordinates and no button.

## 1.10.4 - 2026-10-18

### Farming
- **History:** every finished session (Restart, or logged out for more than 30 minutes) is saved with where it started (zone, sub-zone, coordinates), time, items, gold and gold per hour - in the "Farming" tab, to compare farming spots. Chat shows a short summary when a session ends.
- **Goals:** right-click a marked item -> "Set goal" (20 to 1000 or any amount you own). The farm view shows "120/200" with a progress bar, the tooltip the time left at your current rate, and a notice appears when the goal is reached.
- **Bag space** in the farm view's header (yellow when few, red at the threshold) and a warning once while farming when it runs low (Settings -> Farming -> "Bag space").
- **Item sets:** save your marked items under a name and switch with one click - right-click the farm view's title or "Item sets" in the "Farming" tab.
- Options: hide the farm view in combat, or in dungeons, raids, battlegrounds and arenas (on by default); "Owned" can count all your characters (needs Syndicator, which comes with Baganator).

## 1.10.3 - 2026-10-18

### Farming
- **Raw gold:** gold you loot while a session runs is counted. Gold from mail, the auction house, trades and quest rewards is left out.
- **Merchant income:** what you earn at merchants while a session runs counts separately - except sales of your marked farming items, which already count as "Farmed".
- The farm view's footer shows "Farmed · Raw gold · Merchant" and the **total with gold per hour**. Both can be switched off under Settings -> Farming -> "Gold" (on by default).

## 1.10.2 - 2026-10-18

### Fixed
- The X button closes the Easylife window again.

### Farming
- **Right-click a row** in the farm view: **stop tracking** an item, track an item of the other loot, or **sell it at the next merchant visit** - all stacks in your bags get the merchant module's sale mark (locked items are skipped). A coin on the item icon shows the mark; "Don't sell" removes it again.
- **Always sell** from the same menu, with the usual scope (this character, all characters of the account, all accounts): the rule is added to the sell list and synced, future loot is sold too. A coin stack on the icon shows it; "Stop always selling" removes the rule. If the auction house pays much more than the merchant (over 3x, Auctionator or TSM), chat warns you.
- The "Farming" tab has the same: its "Sell" button opens the sell menu and shows the state ("Marked", "Always").

## 1.10.1 - 2026-10-18

### Farming
- **Other loot:** the farm view lists everything else you gain during a session under "Other loot (n)" (click to show or hide), with amount and gold value. **[+]** tracks an item right away, and what you already looted this session carries over - also when you mark it with the key. The "Farming" tab lists all of it with a "Track" button.

## 1.10.0 - 2026-10-18

### Farming
- New module: mark the items you farm with a key (default **CTRL-F**, hover over the item in your bags or bank). Marked items show a pocket watch in the bag slot and a tooltip line.
- **Farm view:** a small movable window with, per marked item, how many you own, how many you **farmed** this session (starts at zero - what was already in your bags never counts), per hour and gold per hour, plus the session time. **Start/Pause** and **Restart** buttons at the bottom; the "Owned" column can be hidden. Rates appear after 1 minute of farming. Click the title for the new "Farming" tab of the Easylife window.
- The session starts with the first marked item you gain and pauses itself after a few minutes without loot; idle time doesn't count. Purchases, mail, trades and moving items to the bank are not counted.
- Gold values from Auctionator or TradeSkillMaster if installed, otherwise the vendor price. `/el farm` shows or hides the view, `/el farm reset` starts a new session.

## 1.9.0 - 2026-10-14

### Added
- **Overlapping addons:** a few seconds after login Easylife lists installed addons that do what it already does (Vendor, Inventory Guardian, Scrap, Peddler, AutoVendor) and offers to disable them - for this character or all characters of the WoW account - with one click and a reload.
- For **TitanRepair** only its auto-repair and grey selling are switched off; the durability display in Titan Panel stays.
- "Later" asks again at the next login, "Don't ask again" stops asking for these addons. Settings -> Easylife -> "Overlapping addons" ("Check now") or `/el addons` opens the check any time. Replaces the old one-time chat warning.

## 1.8.0 - 2026-10-14

### Added
- Merchant: **sell low-level food and drink** - food whose required level is far below your character (adjustable, default 10 levels). Food without a level requirement is kept.
- Merchant: **sell toys you already know** (soulbound toys that are already in your toy box).
- Merchant: **at most 12 items per visit**, so every sale can still be bought back; the rest is sold at the next visit. On by default.
- The tooltip shows when old food or a known toy will be sold. Food and toys are off by default; switch them on under "Merchant" -> "Sell junk". Together this replaces the addon Vendor.

## 1.7.0 - 2026-10-14

### Added
- Items of your **equipment sets** are protected automatically, like locked items, without locking them by hand. The tooltip names the set. Can be switched off under "Protection".
- Locked items are protected against **scrapping**: they are taken back out of the scrapping machine, and scrapping is stopped while one is inside.
- Locked items are protected against **Disenchant**: while the Disenchant cursor is active, they are greyed out in your bags and can't be targeted.
- Both new protections have their own switches and per-item exceptions ("Options" in the "Locked" tab). Together this replaces the addon Inventory Guardian.

## 1.6.1 - 2026-10-14

### Changed
- Compatible with game version 12.1.5.

## 1.6.0 - 2026-10-14

### Multiboxing
- New module: accepts **group invites**, **shared quests** and (optionally) **summons** from your own characters automatically - this account and your trusted synced accounts. Strangers still get the normal dialog.

## 1.5.0 - 2026-10-06

### Added
- Locked items are protected against **mail** and **trade** too: by default they may only go to your own characters (this account and trusted synced accounts); a protected item is taken back out of the trade window.
- Protection settings per action (sell, destroy, auction house, mail, trade) with **per-item exceptions** in both directions: in the "Locked" tab, "Options" can allow or prevent each action for a single item or lock rule. Exceptions are shown in the tooltip.
- `/el debug` shows in chat what Easylife decides and why; `/el debug log` opens the output in a window for copying - helpful for bug reports.

## 1.4.0 - 2026-10-06

### Added
- Locked items can't be posted to the auction house anymore - in the default auction house, Auctionator and TradeSkillMaster (setting under Protection).

## 1.3.0 - 2026-10-06

### Added
- The glow around **Always sell** items shows where the rule applies: orange = one character, purple = this account, blue = all accounts.
- Tooltips of items covered by an **Always sell** or lock rule name the rule's scope (e.g. "all characters of this account").

### Changed
- Easylife lines in item tooltips are set apart from the game's text by a blank line and shown together as one block.

## 1.2.0 - 2026-10-06

### Added
- Gear icon in the window's title bar: opens the settings page of the current tab.

## 1.1.0 - 2026-10-06

### Changed
- One **Easylife window** with tabs at the bottom - **Locked**, **Sell list** and **What's new** - instead of separate windows.
- The minimap button opens the window directly on the tab you used last; the list keys and commands open their tab and close the window when pressed again.

## 1.0.0 - 2026-10-06

### Item Lock
- Lock any item with a key (default **CTRL-H**): hover it in the character window, bags or bank and press the key again to unlock.
- Locked items are protected: picked-up items are put back at merchants, accidentally sold ones are bought back right away (or a popup offers it), destroying is blocked and a warning appears when you take one off.
- **Lock kind**: lock every item of a kind, for this character, all characters of this account or all your accounts.
- Lock icons in the default bags, the bank and warband bank, the character window and Baganator, plus a tooltip line.
- **Locked items** window: locked items of all characters with search, character filter, collapsible groups and an "Unlock" button; locks of items that no longer exist can be removed with one click.

### Merchant
- Sells grey junk automatically and repairs your gear, using guild funds first if allowed. Hold SHIFT while opening a merchant to skip it once.
- Mark items for the next merchant with a key (default **CTRL-J**); turn a mark into an **Always sell** rule for this character, this account or all your accounts.
- **Sell list** window with marked items and rules; coin icons in the bags, with an orange glow for "always sell" items.
- The chat summary shows the gold actually received.
- Locked items are never sold or marked.

### Account sync
- Shares the lists and rules between your WoW accounts of the same Battle.net account while both are online, without any setup.
- Every other account must be confirmed once; data is only exchanged with trusted accounts. A "Sync" button fetches updates right away.

### General
- Minimap button and addon menu entry; left-click opens the windows, right-click the settings.
- Settings with explanations on every page, modules can be turned on and off.
- German and English.
- **What's new** window after updates (this window).

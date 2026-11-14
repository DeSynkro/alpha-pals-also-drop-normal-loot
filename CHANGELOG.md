# Changelog

All notable changes to Alpha Pals Also Drop Normal Loot are recorded here.

## [1.1] - 2026-11-11

Eight Alpha Pals were getting the drop chance but not the items.

When this mod re-enables a drop, it normally only changes the percentage, because
the game has already put a sensible quantity in the slot. On eight rows the game had
left the quantity at 0 to 0, so a 100% chance still produced nothing. Those rows now
copy the quantity across as well.

- Fixed: Silvance, Ancient Civilization Core
- Fixed: Croajiro, Ice Organ
- Fixed: Nitemary and Nitemary Primo, Dark Fragment
- Fixed: the Guard and Police bosses, their ammunition drops
- No other row changes. Every other drop rate and quantity is untouched.
- Reported by Zippy on the Steam Workshop page.

The generator now refuses to write a change that cannot produce at least one item,
so this class of mistake fails at build time instead of reaching players.

## [1.0] - 2026-10-10

First release.

- Alpha Pals now drop the loot from their normal counterpart as well as their own.
- Covers 319 Alpha rows across the ordinary Pal roster, and 31 rows above level 0,
  which is the World Tree bosses and the MimicDog ladder.
- 669 loot entries switched on in total. 579 of them are a drop chance changed on
  a slot the game had already filled and switched off, and 90 are items added into
  empty slots.
- Nothing that already drops is removed. Every drop the game had switched on is
  left exactly as it was.
- Slot 10 is never written, so this runs alongside the Pals Drop Dog Coins mod
  without either one undoing the other.
- Works with butchering. Butchering rolls the same drop table, so a captured Alpha
  gives a second chance at the same loot.
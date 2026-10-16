# MK Hunting – Changelog

## 1.0.2 – 2026-10-16

### Changed
- Hunting zones no longer run empty: corpses, carried and loaded animals stop counting against the animal limit
- Skinning loot is all-or-nothing – a full inventory never eats the meat any more
- Grill owners can send other players' meat back, and abandoned grills are packed up with refunds
- Bait that attracts nothing is refunded and the cooldown cleared
- Kill reservation now also protects animals in a vehicle at the butcher; knife kills no longer count as headshots
- Black market spots and hours moved to config/server.lua – players can no longer read them
- Discord logs are batched (no more rate limits) and can never ping anyone
- Less server load: cached tablet catalogue, batched quest progress and inventory counts, lighter animal checks, faster log search
- Many small fixes: [E] prompts during actions, tablet prop left in hand, hunting map animations, radar over the grill, trophy double unlocks
- Smaller, tidier corners in every window

## 1.0.1 – 2026-10-15

### Changed
- Cleaner server console: one ready line with the version on start – details only with Config.Debug
- Warnings and errors now use one consistent, prefixed format

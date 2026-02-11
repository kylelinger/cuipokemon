# cuipokemon — Progress

> This file is updated after every completed task/deploy.

## Live
- **Vercel (prod):** https://cuipokemon.vercel.app/
- **GitHub:** https://github.com/kylelinger/cuipokemon

## Current Status (as of 2026-02-10)
### Shipped
- Overworld: Town1/Route1/Town2/Route2/Dungeon1 maps
- NPC interaction: dialogue + quest board + shop NPC
- Dialogue UI: typewriter text, Z to continue, X to speed/skip
- Start menu (Enter): Party/Bag/Save/Close
- Save/load via localStorage (position, team, bag, money, quests)
- Battle loop: Fight/Bag/Run, simple moves + status, bag items
- Capture loop: Ball + shake animation + team add (up to 6)
- Economy: Money system + Shop (buy balls/potions)
- Quests: Quest board with tracking
- Visual upgrade: CC0 Kenney Tiny Town tile loader + loading screen

### In Progress (next)
- Visual upgrade: replace character/monster sprites with generated cartoon pixel sprites (no external assets)
- Polish battle UX (more animations, move descriptions, better pacing)
- Add more quests + dungeon progression

## Changelog
### 2026-02-10
- Added Town2, Route2, Dungeon1 maps.
- Added Shop system (buy items) and Money.
- Added Quest Board system.
- Bugfix: restored JS execution by properly closing the `MAPS` object (was causing green-screen).
- Battle: completed wild/boss battle loop (missing boss moves, status tick damage, paralysis check, burn atk reduction, money rewards).
- Movement: slowed by 20%; fixed cross-map encounter carry-over that could block portals (dungeon exit bug).
- Deployed NPC sprite fix + z-order + sign collision.
- Deployed CC0 Kenney Tiny Town overworld tiles (preload + loading).
- Added PROGRESS.md (this file) and committed to repo.

## Next Tasks (planned)
1. Add Town2/Route2 with new quests
2. Add Dungeon1 + boss fight + reward
3. Add shop + money + item sinks
4. Content pacing for ~1h playtime

## Controls
- Arrow keys: move
- Z: confirm/interact
- X: cancel / speed dialogue
- Enter: open/close Start menu

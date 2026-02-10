# cuipokemon — Progress

> This file is updated after every completed task/deploy.

## Live
- **Vercel (prod):** https://cuipokemon.vercel.app/
- **GitHub:** https://github.com/kylelinger/cuipokemon

## Current Status (as of 2026-02-10)
### Shipped
- Overworld: Town/Route/House maps + portals (door/exit)
- NPC interaction: 2 NPC dialogues + 1 sign
- Dialogue UI: typewriter text, Z to continue, X to speed/skip
- Start menu (Enter): Party/Bag/Save/Close (party/bag basic)
- Save/load via localStorage (position + basic state)
- Battle loop: Fight/Bag/Run, simple moves + status, bag items
- Capture loop: Ball + shake animation + team add (up to 6)
- 10-min demo quest loop: NPC gives 3 balls -> catch 1 -> return -> reward + “Demo Completed!”
- Fixes: distinct NPC sprites + z-order sorting + sign collision
- Visual upgrade: CC0 Kenney Tiny Town tile loader (overworld tiles) + loading screen; removed external font CDN

### In Progress (next)
- Expand world to “1 hour”: Town2 + Route2 + Dungeon1
- Add quest chain (main + side quests), shop/economy
- Upgrade battle depth + more monsters/moves
- Visual upgrade phase 2: replace character sprites with CC0 Q-style sprites (still CC0)

## Changelog
### 2026-02-10
- Deployed NPC sprite fix + z-order + sign collision.
- Deployed CC0 Kenney Tiny Town overworld tiles (preload + loading) and removed external font.

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

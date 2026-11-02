# 🔥 Hot Zone

**A browser first-person shooter. Hold a burning foundry against waves of the infected, or fight your friends in a rain-soaked container yard.**

Everything is in one `index.html`. There's nothing to install or build. It runs in any modern desktop browser.

### ▶ [Play it here](https://hotzonee.github.io/Hot-Zone/)

---

## Game modes

### 🧟 Zombies (solo)
Survive endless waves in **Furnace Hall 2**, a night-shift steel foundry.

- **Infected types:** walkers, runners, burners that throw slag, bloaters that burst in acid, and armoured brutes.
- **Boss:** every fifth wave a **Slag Golem** climbs out of the molten pit. Jump its ground slam and shoot its glowing core, which takes triple damage.
- **Scrap:** kills earn scrap. Spend it on:
  - **Wall buys:** guns hanging on the walls.
  - **The Gunsmith:** a workbench where you fit attachments.
  - **The Forge:** upgrades the gun in your hands through three tiers.
  - **Perks:** Iron Lung (more health), Quick Hands (faster reloads), Fleet Foot (faster movement).
  - **The Mystery Box:** a random gun.
  - **Blast doors:** open up the **Cooling Yard** (ammo cache) and the **Rail Yard** (med station).
  - **The Ladle Pour trap:** tips molten metal into the pit and burns everything around it.
- **Exo suit:** after 50 kills it unlocks, giving you a double jump.

### 🎯 Multiplayer (online)
Free-for-all deathmatch on **Cargo**, first to 30 kills.

- **The map:**
  - a tight yard of stacked shipping containers, with stairs, rooftops and a bridge;
  - a quay with the cargo ship **Orca Star** moored alongside, which you can board by its gangways;
  - a gantry crane overhead, rain, lightning and thunder.
- **Before you play:** build up to **3 loadouts** in the Gunsmith (primary, secondary, melee and attachments).
- **During a match:** medals, kill streaks, a kill feed, a minimap, damage-direction arcs and an end-of-match scoreboard.
- **Grenades** and explosive barrels.

---

## Controls

| Action | Key |
|---|---|
| Move | `W` `A` `S` `D` |
| Jump / sprint / crouch | `Space` / `Shift` / `C` (crouch while sprinting to slide) |
| Shoot / aim down sights | Left mouse / Right mouse |
| Reload | `R` |
| Switch weapon | `1` `2` `3` |
| Knife | `V` |
| Grenade | `X` |
| Lean left / right | `Q` / `E` |
| Interact, Gunsmith, buy | `G` |
| Inspect weapon | `F` |
| Fire mode | `B` |
| Weapon light | `T` |
| Scoreboard | `Tab` |
| Skip intermission (zombies) | `N` |
| Pause | `Esc` |

All keys can be rebound in **Settings → Keybinds**.

---

## Weapons and attachments
11 weapons, from **The Blicky** pistol to the **Hurricane** LMG, including the MP5, Valkyr AR, Breacher 12 shotgun, G3 Marksman, Cross Vec F, Starling L2 and more. You also carry a karambit for melee.

The Gunsmith has **70+ attachments** across optics, muzzles, barrels, underbarrels, rails, grips, stocks, ammo types, magazines and charms. Some examples:

- **Optics:** thermal, night vision and smart scopes.
- **Magazines:** see-through polymer mags that show your remaining rounds.
- **Other:** drum mags and dual-wield.

## Progression
- **XP and levels:** you earn XP in both modes and level up through 55 ranks.
- **Camos:** each gun unlocks Ash, Tiger, Bronze, Gold and an animated **Obsidian** camo as you rack up kills with it.

## Saving your progress
Open **Settings → Save**:
- **Save code:** copy a code, or download a save file, and load it in any browser. No account needed.
- **Cloud save:** sign in with your email (no password) and your progress syncs automatically across every device.

---

## Playing with friends
1. Send your friends the link.
2. Everyone clicks **Multiplayer** and types the **same room code**.
3. Pick a loadout and hit **Join match**.

Different room codes give you separate private matches.

---

## Built with
- [three.js](https://threejs.org) r128 for 3D rendering.
- The Web Audio API for every sound. Gunshots, foley and footsteps are all synthesized at runtime, with no audio files.
- [Supabase](https://supabase.com) for multiplayer (Realtime) and cloud saves (Auth and Postgres).
- Every model, texture and map is built in code: no external art assets.

All brands, ship names and company logos in the game are made up.

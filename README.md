# Wave Keeper

> **Status: Archived / Paused — completed prototype experiment.**
> Wave Keeper served its purpose as Game #1 in the BUILD → SHIP → EARN THE
> FIRST $1 experiment: it proved out rapid vibe-coding with Claude Code and
> a full concept-to-deployable-prototype loop. The game itself was judged
> too simple to charge a stranger for, so it is not being monetized or
> developed further. Code and history are left intact as-is. The next
> game in the experiment lives in its own separate project.

AI-assisted mobile strategy game experiment.

**Objective:** DESIGN → BUILD → SHIP → EARN THE FIRST $1 FROM A STRANGER.
Wave Keeper is Game #1 in that experiment. Speed, fun, and actually
shipping matter more than sophisticated architecture.

## How to run it

`wave-keeper.html` is a single self-contained file — no build step, no
server, no dependencies.

- **Desktop:** open `wave-keeper.html` directly in a browser.
- **iPhone:** host the file (e.g. a quick local static server, or a
  service like GitHub Pages) and open the URL in Safari, or AirDrop the
  file to the phone and open it from Files.

## Current milestone

**Milestone 2 — Player Agency.** Enemies march down one lane; you tap
one of 6 fixed build slots to place a turret when you can afford it.
Turrets auto-target and fire. Kills earn currency, pressure (enemy
health and spawn rate) climbs over time, and eventually your layout
gets overwhelmed. Kills/leaks/best-wave are tracked, with your best
run saved locally so you have something to beat on the next tap of
Restart.

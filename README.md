# 🌳 Treetop Rescue

**Pip & the Glimmer Spirits** — a bright, arcade-style HTML5 platformer in a single file.

Climb an ancient enchanted tree as Pip, a brave little explorer, and free the glowing
Glimmer Spirits caged by **Ratchet**, a mischievous raccoon inventor. Dodge rolling
coconuts, falling beehives and patrolling owls, sling acorns from your trusty slingshot,
and take down four unique bosses on your way to the canopy.

### ▶️ [Play it here](https://dylanong.github.io/treetop/)

*Works in any modern desktop or mobile browser. No installs, no downloads.*

---

## Controls

| Action | Keys |
| --- | --- |
| Move | ← → or A / D |
| Climb ladders & vines | ↑ ↓ or W / S |
| Jump | Space (hold for higher jumps) |
| Sprint | Shift |
| Slingshot | X or F — hold ↑ while firing for a high lob |
| Pause | P or Esc |
| Mute | M |

On phones and tablets, touch controls appear automatically.

## The climb

**8 levels**, each taller and trickier than the last — moving platforms, breakable
bridges, wind currents, waterfalls, slippery ice branches, and dark sections lit only
by fireflies. Every second level ends in a boss fight:

1. 🦉 **Hootmore the Giant Owl** — dodge the swoop, strike while he's dazed
2. 🦫 **The Beaver Engineer** — mind the flying gears, wait for him to tire
3. 🗿 **Mossbound the Golem** — jump the shockwaves, hit the crystal when he kneels
4. 🦝 **Ratchet the Inventor** — the final battle. He gets faster every time you hit him…

Bosses take damage from a stomp on their weak point **or** an acorn pellet — but only
while the weak point is exposed. Any other time, acorns just *plink* off.

## Collect everything

* 🍒 **Fruit** (+50) and 🪙 **coins** (+20)
* 💎 **Gems** — chain them quickly for combo multipliers up to ×9
* 🌰 **Acorn pouches** — slingshot ammo (+3, max 15)
* 🥇 **Golden acorns** — one secret hidden in every level
* ❤️ **Hearts** — extra lives
* **Power-ups:** speed boost, double jump, shield, invincibility leaf, slow-motion hourglass
* Hidden **bonus rooms** — press ↑ at mysterious doors

Checkpoints save your spot, high scores and progress are stored locally in your
browser, and there are 8 achievements to unlock. Rumour has it an old secret code
does something on the title screen…

## Tech

* Single self-contained `index.html` — vanilla JavaScript, HTML5 Canvas, zero libraries
* Object-oriented engine: Player, Bosses, Hazards, Platforms, Particles, Camera, Audio
* Fixed-timestep 60 FPS loop, one-way platform physics with coyote time & jump buffering
* Synthesised chip-tune music and sound effects via Web Audio (no audio files)
* Earth-tone forest palette, parallax backgrounds, dynamic lighting on dark levels
* Responsive 16:9 scaling with touch controls on mobile

## Run it locally

Download `index.html` and open it in a browser. That's it.

---

*An original game inspired by the spirit of classic climb-to-the-top arcade platformers.
All characters, artwork, code and level designs are original creations.*

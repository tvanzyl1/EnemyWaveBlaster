Use the same design philosophy as a juicy emoji-arcade browser game: playful, polished, readable, colourful, and full of animated feedback.

Create a polished top-down zombie wave survival shooter in a single HTML file.

Overall style:
- Match the same playful, polished arcade feel as the “Drunk & Drive” style
- Bright, colourful, slightly neon aesthetic on a darker background
- Clean modern UI with gradients, rounded corners, soft shadows, and bold arcade fonts
- Humorous tone with a bit of chaos and personality
- Use simple shapes and emoji-like readability instead of realistic art
- Add lots of “game juice”: particles, floating text, screen shake, flashes, pickups, juicy hit effects

Game concept:
A lone survivor fights endless waves of zombies in a small arena.
The player moves manually, but weapons auto-fire and auto-aim at the nearest enemy in Vampire Survivors style.

Core gameplay:
- Top-down view
- Player moves with WASD or arrow keys
- Additional virtual stick for mobile movement
- Player does not manually aim
- Weapon automatically targets the nearest zombie in range
- Weapon fires repeatedly on a cooldown
- Zombies continuously spawn and chase the player
- Survive as long as possible
- Score increases over time and for kills
- Waves or difficulty ramp up over time

Combat:
- Default weapon: pistol or magic blaster
- Auto-aim picks nearest valid enemy
- Projectiles travel toward target
- Enemies take damage and die with satisfying feedback
- Add critical hit or headshot-style random bonus text occasionally
- Add optional secondary weapons or upgrades later

Enemies:
- Zombies shamble toward the player
- Mix slow tanky zombies and faster weaker zombies
- Spawn from the edges of the arena
- Increase spawn rate and enemy health over time

Pickups and progression:
- XP gems or drops from dead zombies
-At full XP a bonus drops.
- Health pickups occasionally
- Possible bonusses:
  - faster fire rate
  - more damage
  - piercing shots
  - extra projectile
  - explosion
  - larger pickup radius
  - move speed
  - orbiting projectile or aura damage
  - spinning blades around player
  - a rocket that shoots out every 10 seconds
- Make upgrades feel rewarding and noticeable

Visual style:
- Arena should be readable and attractive
- Player should stand out clearly
- Zombies should be visually distinct by type and colour
- Bullets/projectiles should be bright and satisfying
- Add shadows, glow, pulse, and subtle background motion
- Add death splats, hit sparks, floating damage numbers, and pickup bursts

UI:
- Top HUD with:
  - health bar
  - level
  - XP bar
  - score
  - survival time
  - current wave
- Start screen overlay with big title and play button
- Game over overlay with stats:
  - time survived
  - kills
  - level reached
  - wave reached
  - best score rank

Polish / juice:
- Screen shake on heavy hits or explosions
- Particle effects for bullets, hits, deaths, pickups
- Floating text for damage, crits, level-ups
- Small celebratory effects when levelling
- Smooth animations and readable feedback
- Add funny zombie-related flavour text in menus and upgrade names

Technical constraints:
- Single HTML file only
- HTML, CSS, and JavaScript together
- Use canvas for gameplay
- No external libraries
- Keep code clean and well structured
- Separate sections clearly: state, entities, update loop, rendering, UI

Tone:
- Arcade fun, not horror
- Slightly goofy but satisfying
- Feels like a small premium web game, not a rough prototype

Important:
- Prioritise feel, clarity, and replayability
- Make the auto-aim and auto-fire feel smart and satisfying
- Make the first 30 seconds immediately fun

Add a README.md file to the project at the end

Lean into “mobile arcade polish” with oversized UI, punchy effects, gradient bars, big buttons, playful labels, and visible feedback for every action.
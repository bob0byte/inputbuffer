# Input Buffer

## Input buffer
Tap jump a little **before** you land and the jump comes out on the exact physics tick you touch the ground.
- Cube, ball, robot, spider (ship/UFO/wave/swing already react mid-air)
- Ignores taps meant for orbs
- Adjustable window (default 150 ms)

## Trajectory preview
Two ghost copies of your icon run through the game's real physics every frame:
- **Green**: where you go if you click now
- **Red**: where you go if you don't
- **Yellow**: part of the red path where a tap will be caught by the buffer
- **Red X**: that path dies
- **Blue dot**: that path reaches an orb, pad or portal (the preview stops there)

Everything can be changed in the mod settings.

## Smart Click
Uses the two paths to help you:
- Your click is **ignored** if clicking dies and not clicking is safe
- It **clicks for you** if not clicking dies and clicking is safe (holds in ship, wave and robot)
- If both die, or you're on an orb, you're in full control

A small "Smart Click" label shows in the corner while it's on. It's an auto-play aid, so don't use it for verifying or rated runs.

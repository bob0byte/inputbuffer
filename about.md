# Wave Assist

Everything in this mod only works while you're in **wave**. Other gamemodes play exactly like normal GD.

## Trajectory preview
- **Green**: where you go if you hold / click now
- **Red**: where you go if you let go
- **Red X**: that path dies
- **Blue dot**: that path reaches an orb, pad or portal (the preview stops there)

## Click Shifting
Before applying a press or release, it scans what's in front of you:
- **Big safe area**: your input goes through instantly
- **Small safe area**: your input is moved to the middle of the window, the safest tick
- **Deadly right now**: it waits and applies your input at the safest tick ahead
- **No safe tick at all** (frame-perfect or impossible): your input is cancelled

It steps aside on orbs and dash orbs.

**Auto Click** (off by default) also holds or lets go for you when your current input would kill you.

A small "Smart Click" label shows in the corner while you're in wave with either feature on. These are assist features: don't use them for verifying or rated runs.

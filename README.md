# Daily Arcade

A retro arcade-style productivity tracker. Your weekly routine becomes stages; finishing tasks on time earns XP, combos, streaks, loot drops, trophies and boss kills.

- **Live version (synced across devices):** opened from Claude as an artifact.
- **This repo:** a backup copy of the app source (`index.html`). Opened on its own, it saves progress in that browser only.

## How scoring works
- Check-ins (Wake, Sleep) open 15 min early; blocks can be claimed once they start. Both count as on time until 60 min after the end.
- On time: base XP +25% and a combo multiplier up to x2. Late (same day): half XP. Nothing is taken away.
- Clear a day by finishing 80% of tasks on time. Every 7-day streak earns a streak freeze (max 3).
- Big goals become bosses: each step is a hit, defeating one drops epic-or-better loot.

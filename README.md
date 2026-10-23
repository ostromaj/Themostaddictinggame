# ECHOES

**Every point you score spawns a ghost that replays your exact moves. Don't touch your past.**

Play: https://ostromaj.github.io/Themostaddictinggame/

## How it plays
- Steer with ← → (or A / D). On a phone, hold the left or right side of the screen.
- Grab the ◆. The moment you do, a ghost of you appears and loops the exact route you just took.
- Touch any ghost and you're done. Long, wandering routes make long, dangerous ghosts, so take the short way.
- Every 8th gem is gold and shatters your two longest echoes.

## The hooks
- **Instant retry**: tap anywhere or press space. No menus between you and the next run.
- **"Killed by you from 4.2s ago"**: every death tells you exactly which past self got you.
- **Near-miss feedback**: CLOSE! pops, whooshes, and "2 away from your best" on the results screen.
- **Your score is a song**: each gem plays the next note of a scale, with a literal echo.
- **Skins** unlock at 5, 10, 15, 20, 30, and 45, with a progress bar showing how close you are.
- **Daily course**: 3 tries, same seed for everyone, a share card, and a day streak.
- **Challenge links**: sharing a score creates a `?c=23` link that greets your friend with "Beat 23".

## Tech
One self-contained `index.html` (canvas + Web Audio, no build step, no dependencies). Progress is stored in the browser's localStorage. `og.png` is the link preview image.

# Staging Releases

What to test in each TestFlight staging build, newest first. Entries are added automatically when a staging deploy ships.

[← Back to Main Index](../README.md)

---

## June 17, 2026 — game stats fixes

- Open a Waffle, Number Waffle, or Stackdown stats screen — the star distribution and history are back instead of a blank grey void, now with a "Failed" row for the ones that got away.
- Stackdown stats gain a solve-time distribution chart beneath the stars.
- Strands stats with no hints used should show a tidy empty-state row instead of nothing at all.
- Dialed Daily's average score now reads on its native 0–50 scale, not a mystery percentage.

## June 16, 2026 — NYT Pips

- Share an NYT Pips result (Easy, Medium, or Hard); it should parse, land on the right difficulty, and score on the clock like the other timed games — quicker is better, with cookie credit where earned.
- Assorted housekeeping; if you can see it, it's a bug.

## June 15, 2026 — Wend/Patches + home fixes

- Share a Wend or Patches result (the LinkedIn newcomers); they should parse, score, and land on the board like the regulars.
- Share a Zip result; its score should now agree with the backend instead of inventing its own math.
- Add or remove a game from a party; the home hero should notice and refresh instead of clinging to the old lineup.
- Your own avatar on the home bar and party sheets should show your photo, not fall back to initials.

## June 13, 2026 — LinkedIn share parsing

- Share a Zip, Tango, Queens, or Pinpoint result straight from LinkedIn; it should finally parse and score instead of vanishing into the void.
- Manually log a Pinpoint you didn't solve; it should save as a did-not-finish rather than bouncing back with an error.
- Tap Play on the Home hero card; it should route you to the right place via the standard /home link.

## June 12, 2026 — five LinkedIn games

- Share results from the five new LinkedIn games — Mini Sudoku, Tango, Crossclimb, Pinpoint, and Zip. Each should parse, score, and land on scoreboards and stats like any other game.
- Manual entry works for all five: time picker (with DNF) for the timed four, a 1-5 guess picker for Pinpoint.
- Zip records backtracks; they break ties between equal times but never move the score itself.
- "and flawless" shares count toward flawless stats — including Crossclimb, which it turns out has them.
- Paste a mangled share like "Queens #650 | 1:590" and it should be politely declined, not scored as 1:59.

## June 11, 2026 — Queens time, Mini dates, stat trends

- Tap a Queens result in party chat; the detail popup now shows the solve time instead of pretending you finished instantly.
- Open per-game stats for a guess game (Wordle) and a star game (Waffle); each should show a trend chart of your recent results.
- Share a Mini Crossword result in the old text format; the puzzle date should match the date printed in the share, not whatever day your phone thinks it is.

## June 11, 2026 — Queens + visual fixes

- Share a LinkedIn Queens result, or type one in by hand; it should score on time like the other LinkedIn games, flawless and DNF included.
- On the Games tab, crank text size and browse by category; long names like "Memory & Visual" should no longer clip their game counts.
- Open any game's detail screen; the tinted header should now reach the very top of the screen, no white strip above it.
- Assorted housekeeping; if you can see it, it's a bug.

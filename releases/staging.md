# Staging Releases

What to test in each TestFlight staging build, newest first. Entries are added automatically when a staging deploy ships.

[← Back to Main Index](../README.md)

---

## June 26, 2026 — Direct Messages: push deep-link

- Tap a direct-message push notification; it should drop you straight into that conversation instead of the home screen.
- Tap a DM notification for a thread you already have open; it should stay put rather than stacking a second copy.
- If the conversation has since been blocked or deleted, tapping its notification should land you on home with a brief "couldn't open" note — not a crash or a blank screen.

## June 26, 2026 — Direct Messages + People tab

- People graduates to its own bottom tab: your active-party co-members, searchable by name, sorted by most recent chatter.
- Tap someone for a "You vs them" comparison, then hit Message to open a 1:1 chat — send, delete, and watch the typing dots.
- Mute a chat from its overflow to silence its notifications (it still racks up unread); block or report from the person screen or the chat menu.
- Blocking is silent and quietly drops the person from People; review and undo the fallout under Settings → Blocked Users.
- Share a Crossclimb result copied straight from the app (newline format, no pipes); it should now parse instead of shrugging.

## June 25, 2026 — People surface

- On the Home tab, tap the new "People" toggle beside "Your Parties": you should get a list of folks you share a party with, each tagged with what they last played and when.
- Tap a person to open "You vs [Name]": the games you both play, with your win-loss record per game. Tap a game to drill into the day-by-day head-to-head.
- Someone you've never overlapped with on a puzzle still appears, just with nothing to compare yet. That's expected, not a bug.

## June 24, 2026 — Your Games + per-game standings

- Open the home hero dropdown: games you've played lately now appear under "Your Games," separate from your party games. Nothing played yet? You get a nudge toward the Games tab instead.
- On a party scoreboard, use the new game-selector dropdown to switch from "Overall" to a single game; the list re-ranks by that game and defaults to an All-time view.
- Members with no plays sit in a muted "Hasn't played" footer; if nobody's played it, you get an empty state instead of a blank table.
- Tap a member in a per-game standings list to open the head-to-head: your record, shared days, and a day-by-day who-won breakdown.
- Tap a player's per-game row in the detail sheet; it should jump straight to that game's standings.
- Assorted housekeeping; if you can see it, it's a bug.

## June 21, 2026 — Failed results, recognized

- Paste a Pinpoint loss (the five-thinking-faces "X/5" share); it should record as a failed attempt instead of greeting you with "Unrecognized Format."
- Mark a timed LinkedIn game (Queens, Zip, Tango, and friends) as "didn't solve it" via manual entry; the miss should now show up as a "Failed" row in that game's time stats instead of quietly disappearing.

## June 20, 2026 — Word Search

- Solve the Daily Mini at wordsearch.com (or the bigger Daily Max at /max), share the result, and it should land as a timed game under a new "Word Search" family, scored by how fast you finished.
- Add a Word Search by hand from manual entry; the minutes:seconds picker and the give-up (DNF) toggle should both behave.

## June 20, 2026 — Help guide + Stats polish

- Tap your avatar: Help and Support are now separate items. Help opens a multilevel guide — pick a topic, drill in for answers; Support is just ticket stuff.
- Open a game's solve-time histogram in Stats; bucket labels should read as mm:ss, not a wall of raw seconds.
- Check the Stats Games tab: games now sort by how often you've played them, and ones you've never touched collapse out of the way.

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

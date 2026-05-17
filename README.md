# Cricket Scorer

Ball-by-ball cricket scoring for umpires. Single-page web app, runs offline once loaded, saves matches locally on your device.

## Features

- **Two formats:** Standard limited-overs and Pairs cricket (prep school)
- **Ball-by-ball:** runs, wides, no-balls, byes, leg-byes, wickets (with how-out)
- **Live scoreboard:** team score, batters' scores & balls, bowler figures, current over
- **Undo:** rewind any delivery (last 30 actions)
- **Local save:** every ball auto-saves to your phone via localStorage — no internet needed once page is loaded
- **Resume:** pick up any saved match where you left off
- **Free hit indicator** after no-balls
- **Pairs scoring:** pair runs, –5 per wicket, auto-rotates pairs after their overs

## Add to iPhone Home Screen

1. Open the URL in Safari on iPhone
2. Tap the Share button (square with up arrow)
3. Scroll down and tap **Add to Home Screen**
4. Name it "Cricket" and tap Add
5. App now opens fullscreen like a native app

Saved matches stay on the device. Don't clear Safari data without exporting first (export feature TBD).

## How to use (umpire flow)

1. Tap **+ New Match**
2. Choose format, enter team names, overs, optional player rosters
3. Tap **Start Match** → select opening bowler
4. For each ball, tap one button:
   - **0–6** for runs
   - **Wd / NB / B / LB** → then tap how many additional runs
   - **W** → choose how-out → confirm
5. App handles strike rotation, over completion, end-of-innings, target chasing, result

## Local development

Just open `index.html` in any browser. No build step, no dependencies.

## Hosting

GitHub Pages — push to `main` and enable Pages from repo Settings.

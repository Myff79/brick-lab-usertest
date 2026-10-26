# Brick Lab: participant user test

A clickable prototype of the participant side of Brick Lab. It runs on its own in a browser. No login, no server and no internet needed, except for the AI the tester uses.

## Run it

1. Unzip the folder.
2. Open `index.html` in Chrome or Edge (double-click it).
3. If "Copy picture" doesn't work on your computer, take a screenshot instead: ⌘⇧4 on Mac, Win+Shift+S on Windows.

The tester also needs:
- The AI of their choice, open in another tab or window (Claude, ChatGPT, Codex, Circuit or any other).
- Optional: a bag of LEGO. They can also build on the digital table.

## Two ways to test

Switch at the top of the page.

**Self-paced** (tester alone)
- A welcome box explains the setup. The tester moves on with "Next step" at the bottom.
- The stage is simulated: after 15 minutes of the LEGO task a "Stop building" message appears, a help request gets an automatic reply after about 12 seconds, and two checkpoints arrive 8 and 16 minutes into "Develop it".
- In the learning loop the tester can move freely between "Develop it" and their concept card. "Next step" goes on to the reflection.

**Moderated** (you sit with the tester)
- "Stage controls" in the bottom-right corner is your stage: move between parts, send "Stop building" at the end of the LEGO task, send checkpoints during the learning loop, send announcements or an optional curveball, and answer help requests.
- The step timers start automatically when you move to a step.

## After each session

1. Press **Download test log** at the top. You get a `.json` file with time per step, every click, their notes, card text and help requests. It doesn't include their photos.
2. Press **Restart test** (tap twice) before the next person.

Everything is stored in the browser only. Nothing is sent anywhere.

A full session takes about 50 minutes. The real lab is 65 minutes: 15 intro, 40 in the lab, 10 reflection. See `TEST-GUIDE.md` for what to watch and what to ask.

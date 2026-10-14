# README Template
 
![AI-assisted](https://img.shields.io/badge/provenance-AI--assisted-purple)
 
- The empty line at the end of each box is part of the example. Preview and copy may drop it, so add it back when pasting.
- Blank lines are needed inside `<div>` blocks, otherwise the Markdown inside won't render.
## 1. Title
 
### Without logo, title only
 
````
# Multiple Translator
 
````
 
### Without logo, with Polish name and subtitle
 
````
# Curbs (Krawężniki) — Godot rewrite
 
````
 
### With logo
 
````
<div align="center">
<img src="static/icon512b.png" width="150">
 
# Curbs (Krawężniki)
 
</div>
 
````
 
## 2. Provenance
 
### Handwritten
 
````
![Handwritten](https://img.shields.io/badge/provenance-handwritten-brightgreen)
 
````
 
### AI-assisted
 
````
![AI-assisted](https://img.shields.io/badge/provenance-AI--assisted-purple)
 
````
 
### Vibecoded
 
````
![Vibecoded](https://img.shields.io/badge/provenance-vibecoded-blue)
 
````
 
## 3. History
 
### Original git history
 
````
*2022: original git history*
 
````
 
### Reconstructed git history
 
````
*2022: git history reconstructed from original file timestamps*
 
````
 
### Written before git
 
````
*2016: written before git, first committed in 2026*
 
````
 
## 4. Description
 
### One sentence
 
````
A small, self-guessed prime number generator in Python.
 
````
 
### One sentence, with bold
 
````
A mobile-first scorecard for **Disc Golf Park im. R. Reagana** in Gdańsk — 18 holes, par 58.
 
````
 
### Paragraph, note about status
 
````
A simple app for learning languages by translating the same sentence into multiple languages at once.
 
> Originally deployed on Heroku, back when their free tier made it easy to host small Flask apps. The listing is no longer live since Heroku discontinued free hosting.
 
````
 
### Paragraph, note about a fork
 
````
A full rewrite of [Curbs](https://github.com/nieczuje/curbs-gdevelop), the mobile street-ball minigame originally built in GDevelop, done from scratch in Godot. Built as a learning project to compare the two engines (this Godot build was never released).
 
> Co-developed with [Ravenyy](https://github.com/Ravenyy) — forked from [his original repo](https://github.com/Ravenyy/Godot-Curbs) to keep the real collaborative commit history intact.
 
````
 
### Story with P.S.
 
````
Before I learned to program, I pushed spreadsheet formulas to their absolute limit. This is one surviving cell — a single formula roughly two A4 pages long, used for a forex take-profit/stop-loss calculation.
 
Duplicating this formula across multiple cells reliably broke the spreadsheet. That breaking point is basically what pushed me to start programming for real.
 
Each cell reference is color-coded consistently throughout — which made it *feel* more readable. It wasn't.
 
*P.S. Want to see the actual mess behind it? [Draft history](draft-history.txt) shows every half-finished attempt, merge, and dead end along the way.*
 
````
 
## 5. Features (Optional)
 
### Feature list
 
````
## Features
 
- Hole-by-hole scoring with +/- steppers
- Live leaderboard across players
- Embedded course map tab
- Self-contained single-file app — no build step, no server, no dependencies. Open `index.html` and go.
 
````
 
## 6. How it works (Optional)
 
### Numbered steps
 
````
## How it works
 
1. Choose the languages (up to 9)
2. Write a sentence or generate one by clicking "GO"
3. Before unfolding each translation, try to translate the sentence in your mind
4. Unfold all translations, then repeat from step 2
 
````
 
### Bullet list
 
````
## How it works
 
- Pick a numbered locker ("skrytka")
- Choose an emoji from the picker
- Set a 4-digit PIN
- Get a shareable link + PIN — opening the link and entering the PIN unlocks the matching locker and reveals the emoji
 
````
 
### Paragraph
 
````
## How it works
 
Every prime greater than 3 leaves a remainder of 1, 5, 7, or 11 when divided by 12. `primes_rows` walks these four number lines at once (`row = [1, 5, 7, 11]`, each stepping by 12), and for each candidate checks it against a running list of known primes' future multiples — rather than testing divisibility directly. If a candidate matches one of those tracked "not-prime" values, it's composite and the tracker jumps ahead by `12 * prime`; otherwise it's prime, and it gets its own tracker seeded from its square.
 
````
 
## 7. Structure (Optional)
 
### Folder list
 
````
## Structure
 
- Root (`index.php`, `index.js`, `style.css`, `emojis.php`) — the final, deployed version of the app
- `legacy/` — the original vanilla JS/HTML prototype this grew from (Oct–Dec 2021), kept for history. See `legacy/emotkomat.php` for an even earlier, pre-jQuery first attempt.
 
````
 
## 8. Demo (Optional)
 
- The widths in the examples are tested values. Don't change them without checking the GitHub preview.
- Table header lengths affect image width.
### Desktop screenshots
 
- Landscape screenshots (widescreen 16:9, e.g. Full HD or 4K): 2 per row, `width="400"`.
````
## Demo
 
| Sending (nadawczy) | Receiving (odbiorczy) |
|---|---|
| [<img src="screenshots/2.png" width="400">](screenshots/2.png) | [<img src="screenshots/4.png" width="400">](screenshots/4.png) |
 
````
 
### Mobile horizontal screenshots
 
- Phone screenshots taken horizontally: 2 per row, `width="400"`.
````
## Demo
 
| Rules | Gameplay (Level 6/6) |
|---|---|
| [<img src="screens/phone/1.png" width="400">](screens/phone/1.png) | [<img src="screens/phone/3.png" width="400">](screens/phone/3.png) |
 
````
 
### Mobile vertical screenshots
 
- Portrait phone screenshots: 5 per row, `width="170"`.
````
## Demo
 
Fully responsive — works the same on desktop and mobile.
 
| Start | More languages | Generated, folded | Unfolded | Next sentence |
|---|---|---|---|---|
| [<img src="screenshots/11mobile_start.png" width="170">](screenshots/11mobile_start.png) | [<img src="screenshots/12mobile_more_languages.png" width="170">](screenshots/12mobile_more_languages.png) | [<img src="screenshots/13mobile_easy_generated.png" width="170">](screenshots/13mobile_easy_generated.png) | [<img src="screenshots/14mobile_easy_generated_unfold.png" width="170">](screenshots/14mobile_easy_generated_unfold.png) | [<img src="screenshots/15mobile_your_sentence.png" width="170">](screenshots/15mobile_your_sentence.png) |
 
````
 
### YouTube video
 
- Video ID: the part after `v=` in the YouTube link, or after `youtu.be/` in the short link (here `1KLDA0Ikamk`).
- Thumbnail link: `https://img.youtube.com/vi/VIDEO_ID/maxresdefault.jpg`, shown at `width="500"`.
- Thumbnail sizes: `maxresdefault` 1280×720 (may be missing for older or low-resolution videos), `sddefault` 640×480, `hqdefault` 480×360, `mqdefault` 320×180, `default` 120×90.
````
## Demo
 
| [![YouTube](https://img.shields.io/badge/YouTube-Watch_full_walkthrough-red?logo=youtube)](https://youtu.be/1KLDA0Ikamk) |
|---|
| [<img src="https://img.youtube.com/vi/1KLDA0Ikamk/maxresdefault.jpg" width="500">](https://youtu.be/1KLDA0Ikamk) |
 
````
 
### YouTube video, not ready yet
 
- Put this line where the video thumbnail will go, and replace it when the video is ready.
````
*(gameplay video to be added)*
 
````
 
## 9. Usage
 
### Live link and offline copy
 
````
## Usage
 
**Easiest — use it live, no download needed:**
Open [nieczuje.github.io/disc-golf-scorecard](https://nieczuje.github.io/disc-golf-scorecard/) in your phone's browser. For a home-screen "app" feel, use "Add to Home Screen" from the browser menu.
 
**Offline / standalone copy:**
Download `index.html` from this repo and open it directly in a browser — the whole app is self-contained in that one file, so it works without internet access once downloaded.
 
````
 
### Command to run
 
- The example contains a code block itself, so the outer box uses four backticks.
````
## Usage
 
```bash
python primes.py
```
 
Prints all primes up to the limit set by `primes_rows(1020)` at the bottom of the file. Change that number to adjust the range.
 
````
 
## 10. Tech
 
### Short list
 
````
## Tech
 
Python, Flask, some JavaScript, Bootstrap. Translations via the googletrans Google Translate Ajax API.
 
````
 
### With details
 
````
## Tech
 
Vanilla HTML/CSS/JS. All assets (logo, course map) are base64-embedded directly in the HTML, so the whole app is one file you can drop anywhere — no CDN, no build pipeline required to *run* it.
 
````
 
## 11. Extra sections (Optional)
 
- The section names are free-form: choose the ones that fit the project. The headings below are the names used so far.
- These sections go after Tech and before License.
- If used, Notes goes last.
### About
 
````
## About
 
The original GDevelop version was the one actually submitted to Google Play (Feb 2022) as "Curbs minigame"; this Godot rewrite followed as a side project and was never published. Mechanically and visually it plays almost identically to the original — same rules, same look — since the point was comparing engines, not redesigning the game. See [curbs-gdevelop](https://github.com/nieczuje/curbs-gdevelop) for screenshots and gameplay video, since they'd look effectively the same here.
 
````
 
### Development history
 
````
## Development history
 
This repo's git history is reconstructed from the real timestamps of the original project files (saved locally rather than version-controlled at the time) — every commit date reflects when that save actually happened, from the earliest prototype (Feb 3, 2022) through the final build submitted to Google Play (Feb 18, 2022). The `builds/` folder keeps every APK/AAB iteration along the way. `experiments/randomized_levels/` is a side experiment with a shuffled level order.
 
````
 
### How this was found
 
````
## How this was found
 
Before any code existed, this was worked out by hand in a spreadsheet. Laying numbers 1 through 1000+ out in rows of 12 made a pattern visible immediately: every prime greater than 3 lands in one of only four columns. From there, tracking where each prime's multiples actually fell — by hand, cell by cell — revealed the exact offsets now hardcoded in `primes_rows`: `+2, +6, +8` times the prime for one pair of columns, `+4, +6, +10` for the other, repeating every 12× the prime.
 
The third sheet below ("All primes") colors every number each prime (5, 7, 11, 13...) predicts as composite, starting from that prime's own square — a hand-run, color-coded version of the exact algorithm the code now runs automatically.
 
**In the "All primes" sheet, the numbers left uncolored in those four columns are the primes themselves.**
 
*Legend: P = Pythagorean primes column, G = Gaussian primes column, E = Eisenstein primes (without imaginary part) column.*
 
````
 
### Notes
 
````
## Notes
 
- Course logo and map images are inlined as base64 to keep the app a single portable file.
- Logo is AI-generated from an original photo I took.
 
````
 
## 12. Credits (Optional)
 
### One credit
 
````
## Credits
 
- Title font: [Luckiest Guy](https://fonts.google.com/specimen/Luckiest+Guy), Apache License 2.0.
 
````
 
### Several sources with citation
 
````
## Credits
 
- Sentence data: [GenericsKB](https://huggingface.co/datasets/generics_kb), Allen Institute for AI — CC BY 4.0. Citation: Bhakthavatsalam, S., Anastasiades, C., & Clark, P. (2020). *GenericsKB: A Knowledge Base of Generic Statements*.
- Example sentences also drawn from [englishstudyhere.com](https://englishstudyhere.com/sentences/1000-sentences-examples-in-english/), [7esl.com](https://7esl.com/english-verbs/), [englishspeak.com](https://www.englishspeak.com/en/english-phrases?category_key=20), and [onlymyenglish.com](https://onlymyenglish.com/1000-english-sentences-used-in-daily-life/).
 
````
 
## 13. License (Optional)
 
### MIT
 
````
## License
 
MIT — see [LICENSE](LICENSE).
 
````
 
## 14. Final images (Optional)
 
- An optional legend line goes first, above the images.
### Stacked
 
- One image under another, no width set.
````
![The formula](formula-colored1.png)
![The formula](formula-colored2.png)
 
````
 
### Columns
 
- Images side by side in a table, `width="280"` for 3 columns.
- Table header lengths affect image width.
````
*Legend: P = Pythagorean primes column, G = Gaussian primes column, E = Eisenstein primes (without imaginary part) column.*
 
| Prime of 5 | Prime of 7 | All primes |
|---|---|---|
| [<img src="screenshots/sheet-5.png" width="280">](screenshots/sheet-5.png) | [<img src="screenshots/sheet-7.png" width="280">](screenshots/sheet-7.png) | [<img src="screenshots/sheet-all.png" width="280">](screenshots/sheet-all.png) |
 
````
 



text
I want to create a highly premium, animated GitHub Profile README featuring dynamic, self-contained SVG files. Please write Python scripts that generate three high-end SVG files using pure SMIL animations (no external CSS or JS dependencies). 
Here are the strict requirements for the aesthetic and files:
1. **Aesthetics & Vibe:** 
   - Deep dark mode (#0d1117 background, glassmorphism, cinematic glows).
   - Cyberpunk/Developer aesthetic with neon accents (cyan, green, orange, purple).
   - High frame-rate, smooth CSS/SMIL animations built directly into the SVGs.
2. **File 1: `github-contribution-animation.svg` (Contribution Graph)**
   - Create a Python script to generate a 53x7 GitHub contribution calendar.
   - **Animation:** Implement a diagonal "slant reveal". The squares should sweep in from the bottom-left to top-right.
   - **Effects:** As each square appears, it should have a brief, bright white/green "glint" or specular highlight that flashes and fades out, settling into its normal contribution color. Level 3+ squares should have an outer glow filter.
3. **File 2: `terminal-card.svg` (ASCII Portrait Terminal)**
   - Create a Python script that fetches a GitHub avatar (using my username) and converts it into dense ASCII art using `Pillow`.
   - **Animation:** Place this ASCII art inside a macOS-style terminal window. Animate the ASCII art revealing row-by-row, top-to-bottom, with a white cursor block sweeping left-to-right across each row.
   - **Footer:** Add a typewriter animation at the bottom simulating `$ whoami` followed by the user's name.
4. **File 3: `info-card.svg` (Neofetch Info Card)**
   - Create a smaller, neofetch-style card that sits next to the ASCII portrait.
   - Include sections for About, Stack, and Highlights using colors (Orange, Blue, Green, Cyan, White).
   - **Animation:** Each line should slide up and fade in with a staggered delay (0.06s between each row) to simulate a terminal printing the neofetch output.
5. **README Integration:**
   - The Python script should automatically inject the `terminal-card.svg` and `info-card.svg` side-by-side using an HTML `<table>` into the `README.md`, and place the `github-contribution-animation.svg` centered below it.
Please provide the complete, ready-to-run Python code for this setup.
max&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://komarev.com/ghpvc/?username=shadiisthesameasfelicity-max&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

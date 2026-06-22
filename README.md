# BIG — big-screen display

A tiny, single-file web app that shows any number or word **huge** on the screen.
Type or pick a value and it fills the screen, crisp and auto-fit. An optional
left-to-right **scroll / marquee** mode keeps long text big and glides it across.

**Live:** https://charlot3.github.io/big-screen/

## Features

- Big auto-fit typography — numbers and short words fill the screen
- Preset chips + a live custom input (type anything, Enter to commit)
- Optional horizontal **scroll / marquee** mode with an adjustable, constant speed
  (px/sec, so long and short text scroll at the same visual pace)
- 5 themes, fullscreen (`F`), keyboard: `Enter` = show, `Esc` = clear
- A single self-contained `index.html` — **zero dependencies, works offline**

## Run locally

Just open `index.html` in any browser. No build step, no server, no internet required.

## Deploy

It's a static single file. GitHub Pages serves `index.html` from the repo root.
Drop the file anywhere that serves static files and it works.

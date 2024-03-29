# ➿REW-p5
Porting and upgrade of [REW](https://github.com/danieledep/REW) game from Processing to P5.js.
A new chapter of the same music cassette whose tape keeps unrolling out of place until some brave spinning wheels will find its way to harness the tape. It has performance issues to fix.

## Controls
- <kbd>&#8592;</kbd> or <kbd>A</kbd> to make the wheel turn left
- <kbd>&#8594;</kbd> or <kbd>D</kbd> to make the wheel turn right
- <kbd>&#8593;</kbd> or <kbd>W</kbd> to eject a new wheel   
- <kbd>Space</kbd> or <kbd>Left click</kbd> to pause/unpause the game   
- <kbd>R</kbd> to take a screenshot


![screenshot](https://github.com/danieledep/REW_P5/blob/master/assets/Screenshot-23-07-2022.png)

## To-dos
- [x] add record button ⏺ to save a screenshot
- [x] move score text to canvas
- [x] make controls work well on mobile
- [x] fix bouncing direction bug
- [x] when intersecting tape update tape also for wheel n-1 and n+1
- [x] wheel speed should go faster as game advance
- [ ] update html2canvas when it supports `mix-blend-mode`, [#2839](https://github.com/niklasvh/html2canvas/pull/2839)
- [ ] build hardware controller

## Misc.

![Tape Loop-Labyrinths](https://github.com/danieledep/REW_P5/blob/master/assets/tape-loop-labyrinths.jpg)   
*[The Tape Loop Labyrinths](https://www.tabsout.com/?p=17050) from Justin Lakes, not the inspiration for this project but still a great concept*

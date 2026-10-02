# 🍉 Fruit Slice

A fast, juicy fruit-slicing game that runs in your browser. Swipe on a touch screen or glide your laptop trackpad to slice fruit, dodge the bombs, and chase a high score.

**▶ Play now:** https://YOUR-USERNAME.github.io/fruit-slice/

<!-- Add a screenshot or GIF here: ![Gameplay](screenshot.png) -->

## Features

- Touch and trackpad/mouse support. On a laptop, just move the cursor over the fruit, no click needed
- 8 fruits that are cut along your exact swipe line, with the two halves flying apart
- Juice spray, juice stains, blade trail and cut flash effects
- Combo bonus for slicing 3 or more fruits in one swipe
- 3 lives, bombs, and difficulty that ramps up over time
- Sound effects with a mute button
- Best score saved in your browser
- Single file, no dependencies, no build step

## How to play

| Action | Result |
| --- | --- |
| Slice a fruit | +1 point |
| Slice 3+ fruits in one swipe | Combo bonus |
| Let a fruit fall | Lose 1 life (3 lives) |
| Slice a bomb | Game over |

## Run locally

1. Download or clone this repository
2. Open `index.html` in any modern browser

```bash
git clone https://github.com/YOUR-USERNAME/fruit-slice.git
cd fruit-slice
# then just open index.html
```

## Customize

- **Fruits:** edit the `TYPES` list near the top of the script (emoji, cut-face colour, juice colour, size)
- **Difficulty:** edit the `wave()` function (fruits per wave, bomb chance) and the spawn timing in `frame()`
- **Colours:** edit the CSS variables at the top of the `<style>` block

## Tech

Plain HTML, CSS and JavaScript with the Canvas 2D API and Pointer Events. Sounds are generated with the Web Audio API. Fruits are drawn with the device's emoji font, so they look slightly different on each platform.

## Credits

Built with help from [Claude](https://claude.ai) by Anthropic.

## License

[MIT](LICENSE)

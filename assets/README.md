# Profile animation

`banban-header.svg` uses the actual Pixel Banban artwork from the public [Banban desktop release repository](https://github.com/yuzhang-zhong/banban-desktop-releases):

- [Daily motion](https://github.com/yuzhang-zhong/banban-desktop-releases/blob/main/media/daily-motion.gif), source blob `1ff9b98010e87dd0f98779e282049a55d2378197`: sitting, blinking, stretching and walking.
- [Toy motion](https://github.com/yuzhang-zhong/banban-desktop-releases/blob/main/media/toy-motion.gif), source blob `dbb84176275ccae3d56e07c513d1e29d21b9a17d`: alert head tilts and playful crouches.
- [Sleep motion](https://github.com/yuzhang-zhong/banban-desktop-releases/blob/main/media/sleep-motion.gif), source blob `f58e2913a79df5b16c41d7138f5f9df83b7b41f1`: curled-up resting poses.

Original GIF frames were cropped into 24 equal sprite cells. Only the connected exterior pale backdrop was made transparent; the cat artwork was not recolored, redrawn, or generated.

The self-contained SVG embeds its sprite sheet, with no scripts, tracking or remote dependencies. A tiny 26px sprite moves inside a 52 × 28 image beside the profile name, with varied original poses over a 24-second loop. `prefers-reduced-motion: reduce` replaces the motion with a still original pose. The animation stays within its image; it does not overlay the rest of the GitHub page.

`banban-caption.svg` provides the adjacent 9px English character credit, with light- and dark-mode text colors. The earlier `banban-walk.svg` is retained as an unused asset.

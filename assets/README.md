# Profile animation

`banban-walk.svg` uses the actual Pixel Banban artwork from the [public daily-motion GIF](https://github.com/yuzhang-zhong/banban-desktop-releases/blob/main/media/daily-motion.gif) (source blob `1ff9b98010e87dd0f98779e282049a55d2378197`).

- Original GIF frames were cropped into equal sprite cells. Only the connected exterior pale backdrop was made transparent; the cat artwork was not recolored, redrawn, or generated.
- The SVG embeds the sprite sheet, with no scripts or remote dependencies.
- A 48px cat walks inside a 600 × 80 strip, turning at each edge over a 16-second round trip.
- `prefers-reduced-motion: reduce` replaces the motion with a still original pose.
- The animation is confined to its image; it does not overlay or move across the rest of the GitHub page.

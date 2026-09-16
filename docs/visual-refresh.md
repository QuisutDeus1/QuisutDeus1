# Profile visual refresh

## Images

- `img/western-banner.png`: original artwork generated with the built-in imagegen tool. The full prompt is in [western-banner-prompt.txt](western-banner-prompt.txt).
- `img/opentakeoff-poster.png`: existing poster, unchanged.
- `img/opentakeoff-workspace.png`: fresh 1600 × 1000 browser screenshot of https://opentakeoff.kentucky-ai.com, captured September 16, 2026 UTC with a clean browser context and the bundled public sample plan. No customer workspace was loaded. Reproduce: use a fresh desktop browser, load the sample plan, and leave the Premium workspace in its default graphite appearance with dark system color scheme.
- `img/opentakeoff-sweep.png`: unmodified screenshot from [OpenTakeoff's latest merged annotation release](https://github.com/Kentucky-ai/opentakeoff/blob/f4781ae0609978c4313e30633b2d43a9e8e863f4/docs/reviews/premium-annotations/text-sweep.png). This shows the bundled public sample, with 25 of 26 CPT-1 matches selected. [Source review and reproduction steps](https://github.com/Kentucky-ai/opentakeoff/blob/f4781ae0609978c4313e30633b2d43a9e8e863f4/docs/reviews/premium-annotations/README.md).

The hotel recording remains linked as an earlier-interface video. The new screenshots do not represent frames from that recording. Older image files remain available for historical references.

## Review evidence

The README was rendered through GitHub's Markdown API and checked in desktop light, desktop dark, and narrow layouts. Screenshots are in [review](review/). This is a visual/content refresh; it does not change or retest the OpenTakeoff engine.

Validation: `git diff --check`, verify that every relative README image exists, and inspect the rendered screenshots. The original OT poster's SHA-256 must match the parent commit.

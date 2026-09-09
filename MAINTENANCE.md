# Profile maintenance

`README.md` is displayed on github.com/Rorogogogo because this public repository matches the account name.

## Design

An editorial layout: one SVG masthead, a short introduction, two featured project previews, and four more projects in a native Markdown table. The masthead combines serif typography with one fine-line abstract form. All artwork is monochrome. Project names and descriptions are live text so they stay readable, selectable, and searchable.

The masthead uses four files: light/dark covers and their compact phone versions. Each is a self-contained SVG with accessible text, no remote resources, and no scripts or animation. The README uses picture sources to select the appropriate version.

The selected projects are NoMoreIDE, JobJourney Assistant, Claude Cracks the Whip, Notchy, Baton Pass, and Breath of the Builder. Keep descriptions short and links direct. Avoid adding badges, metrics dashboards, repeated banners, or more decorative graphics.

## Project previews

The two featured projects use real screenshots restored from the original profile. Each `*-preview.svg` embeds its corresponding `*-source.png` and applies a grayscale SVG filter. The original screenshots stay unmodified, and displayed previews remain black and white. Text, layout, and proportions are preserved. Clicking a preview opens its project repository.

Sources:
- `nomoreide-source.png`: `Rorogogogo/nomoreide`, `assets/screenshots/product-tour.png`.
- `jobjourney-source.png`: `Rorogogogo/Jobjourney-extention`, `chrome-extension/public/Global_dasboard.png`.

When replacing a source screenshot, regenerate the embedded base64 data and dimensions in its SVG wrapper.

## Suggested GitHub pins

In the profile's **Customize your pins** UI, select these six repositories:

1. nomoreide
2. Jobjourney-extention
3. claude-cracks-the-whip
4. Notchy
5. baton-pass
6. breath-of-the-builder

The README already links to all six. Pins are a separate GitHub profile setting.

# Region with fixed width

Captures a region you select and gives every capture the same width: wider images are scaled down to the maximum
width, smaller images are placed on a canvas of that width. A border is added if you like. The result goes to your
export destinations.

Handy for documentation and tickets, where all screenshots should look the same width.

## Use it

- Hotkey: Ctrl + Alt + F, change it in Greenshot's Settings > General (hotkeys) or in the recipe editor
- Right-click context menu

## Options

| Option | Default |
|---|---|
| Hotkey | Ctrl + Alt + F |
| Max width (px) | 800 |
| Add border | on |
| Border thickness (px) | 2 |
| Border color | black |
| Fill up smaller images | on |
| Canvas color | gray (#888888) |

The border is counted into the width: with a 2 px border the image is scaled to the max width minus 4 px, so the final
image is exactly as wide as the max width.

## Allows

Nothing beyond the capture itself and your export destinations.

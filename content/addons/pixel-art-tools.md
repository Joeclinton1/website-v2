---
id: pixel-art-tools
draft: true
---

**Pixel art tools** adds a small pixel canvas, color palettes, brush size shortcuts, and an animation preview to Scratch's bitmap costume editor.

## Usage

### Starting a pixel costume

1. Open the Costumes tab and choose a bitmap costume. Use **Convert to Bitmap** if your costume is in vector mode.
2. Turn on **Pixel Mode** beside the zoom controls.
3. Set the canvas width and height using the two fields beside the Pixel Mode button. Press Enter or leave the field to apply a size.
4. Draw with Scratch's bitmap tools. The brush and line tools have shortcuts for sizes 1 through 4.

The middle zoom button (`=`) fits the pixel canvas in the editor. You can still zoom in and out with the neighboring buttons.

An empty vector costume becomes a 1 by 1 bitmap when converted. To create several costumes at a consistent size, enable **New paint costumes are bitmap by default** in this addon's settings and choose a default width and height. You can also enable **Enable pixel mode by default** to start with Pixel Mode turned on.

When you select an existing bitmap costume, the pixel canvas follows that costume's dimensions. Default width and height do not resize existing artwork. Manually entered odd dimensions round up to an even number to match the bitmap size conversion.

### Color palettes

Choose a fill color in Scratch, then click the palette's **+** button to save it. A palette can contain up to 64 different colors.

- Click a swatch to use its color.
- Shift-click a swatch to edit it, then change the fill color in Scratch. Shift-click the swatch again to finish editing.
- Right-click a swatch to remove it.
- Use the dropdown to switch palettes or create another palette.
- Use **Import** to load a GIMP `.gpl` palette, a text file containing hex colors, or colors from an image.
- Use **Export** to download the selected palette as a text file.
- Use **Delete Palette** to remove the selected palette after confirmation.

Palettes are saved in project comments, along with each costume's palette choice. Keep those comments if you want to preserve the palettes when saving and reopening the project. Use Scratch's costume undo and redo controls to undo adding, removing, or editing swatches; creating, importing, and deleting whole palettes are not included.

Colors used when drawing are added automatically. Undoing the drawing also undoes its new swatch, and continuous adjustments to a swatch's color undo as one edit.

In a narrow editor window, the palette floats over the canvas. Drag its header to move it.

### Animation preview

The preview cycles through the current sprite's costumes. Use the play/pause button to pause it and the FPS slider to change playback speed. Expand the range controls to choose the first and last costumes to include; numbering starts at 1.

Click **Export GIF** or the preview image to export the animation. Drag the panel's header to move it, or hide the panel using **Hide animation preview** in the addon settings.

### Costume size on the stage

Imported bitmap costumes appear at half their original size. To display a sprite at full size, put the Looks block **set size to (200) %** in its code. This is a Scratch block, separate from the width and height fields in the costume editor.

## Settings

### Default width and Default height

Choose the size for new costumes created with **New paint costumes are bitmap by default**. Both default to 32.

### Enable pixel mode by default

Start with Pixel Mode enabled for bitmap costumes. This setting is off by default.

### New paint costumes are bitmap by default

Create new painted costumes as bitmaps at the configured default dimensions. This setting is off by default.

### Prevent automatic bitmap trimming

Keep the selected pixel canvas dimensions when drawing, including empty space around the artwork. This setting is on by default and applies while Pixel Mode is active.

### Hide animation preview

Hide the floating animation panel. This setting is off by default.

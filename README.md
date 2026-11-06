# 声页 · Podcast Cover Studio

A standalone podcast cover editor with a cool, grainy retro-futurist visual style. The interface is in Chinese.

[Open the live editor](https://mengxuebi-mush.github.io/podcast-cover-studio-site/)

## Open the editor

Download or clone this repository and open `index.html` in a modern browser. No installation, build step, server, or external dependencies are required.

## Features

- Upload a photo from your device, or drag and drop it into the editor.
- Choose an oval record window, cassette window, speech bubble, or arch.
- Add title and supporting text layers, edit multiline copy, and drag each layer on the canvas.
- Set each text layer’s size, width, weight, alignment, and color.
- Drag, zoom, and crop the original photograph inside the selected shape.
- Adjust the photo window's size and position independently from the photo zoom.
- Keep a separate crop for each shape while switching templates.
- Export an opaque 1080 × 1440 PNG with the shared background, audio waveform, and the podcast name “蘑菇秘语 Mushroom Whipsers”.
- Use mouse, touch gestures, or arrow keys to adjust the composition.

## Photo handling

All photo processing happens locally in the browser. Photos are cropped, resized, and clipped into a shape; the editor does not generate or redraw people. Uploaded photos are not sent to a server or saved back into this repository.

The published editor starts with an empty photo placeholder and contains no embedded personal photograph. Uploaded images and crop settings stay in the current browser session and are not saved after closing or reloading the page.

## Controls

- **拖动照片**: drag the photograph inside its window.
- **移动照片窗**: move the whole window on the cover.
- **照片窗大小**: resize the window while preserving the photo zoom setting.
- **窗内照片缩放**: zoom the photograph inside the window.
- Use the mouse wheel or a two-finger pinch to zoom over the photo.
- Focus the preview and use arrow keys to nudge; hold Shift for larger steps.
- Remove the photo to export an empty template.

Add a title or text layer with **添加标题** or **添加文字**. Select a layer on the canvas and drag it to place it; double-click to edit its content. Text wraps to the chosen width and is included in the exported PNG. Direction keys nudge the selected text; Delete removes it when the canvas has focus. Text layers are shared across the four shape templates, while photo crops are stored separately for each shape.

# Story 01: ぼくの あたらしい 学校

**[Open playable HTML](index.html)**

This is a single-file HTML/CSS/JavaScript story workshop. It is designed for direct review and iterative changes, and does not depend on the main AIKO app.

## Chapters
1. Morning (scenes 01–06)
2. Going to School (07–10)
3. Start of School (11–14)
4. New Faces (15–18)
5. End of the Day (19–24)

Each scene presents a standalone camera-view illustration placeholder and 3 clickable action objects. After completing the actions, answer one simple Japanese fill-in question. Completing it unlocks the next picture. English translations can be toggled in the header. Replay any previously completed scene. Progress uses localStorage on the same browser.

## Replace artwork later

Drop matching images here:

`images/scene-01.webp` through `images/scene-24.webp`

The HTML tries these paths and falls back to its built-in illustrated scene layout if a file is absent. The hotspots and Japanese text stay as HTML overlays rather than being baked into the art. For best results, use portrait 4:5 or 9:16 images and leave room around interactive objects.

## Edit story content

Scenes are in the `S` array inside `index.html`. Each entry includes the title, Japanese title, visual placeholders, colors, dialogue, English translation, fill-up, answer options, correct index, and three interactive actions.

Story 01 is a prototype intended for visual feedback, not a final animation engine. Drag/swipe animations and spatially exact object hotspots can be developed after artwork is approved.

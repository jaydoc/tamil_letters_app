# Tamil Kids Letters – combined app

This version combines:

- Uyir / Mei letter cards with audio
- ✏️ Trace tab with Teacher mode, smoothed strokes, slower demos
- 🎮 Game tab (Find the Sound)
- 📚 Activities tab with the MSU Basic Tamil H5P vowel-sorting activity embedded

## Files

- index.html   – main app
- strokes.js   – stroke data placeholders (fill as you record letters)
- audio/       – put your MP3 files here (e.g., uyir_a.mp3, mei_k.mp3)

## Activities tab (H5P embed)

The Activities tab loads:

  https://openbooks.lib.msu.edu/basictamil/wp-admin/admin-ajax.php?action=h5p_embed&id=3

and injects the official H5P resizer script so it auto-sizes inside your app.  
Internet is required for this tab to work; everything else works offline.

## Tracing / Teacher mode workflow

Same as before:

1. Go to Trace tab.
2. Turn on Teacher mode (checkbox).
3. Click ⏺ Start recording, draw the letter, then ⏹ Stop & save.
4. The app smooths the stroke and saves it in `localStorage` and in the in-memory STROKE_DATA.
5. Copy JSON from the export box and paste into strokes.js for a permanent definition.


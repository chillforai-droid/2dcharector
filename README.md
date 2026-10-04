# Character Layer Studio
No-AI, client-side 2D character layer cutter.

## Run
Open `index.html` in a modern browser. For ZIP export, internet is needed for the JSZip CDN; otherwise individual PNG downloads and JSON export work offline.

## Workflow
1. Upload Front view.
2. Select a part.
3. Draw a polygon around it.
4. Extract.
5. Repeat.
6. Upload Back and repeat if needed.
7. Download PNGs or ZIP.

## Important
This tool separates pixels from the supplied image. It does not reconstruct pixels hidden behind other parts. For animation-ready art, upload a clean full-body character with visible limbs and use Clone/Paint in a future editor version to repair occluded areas.

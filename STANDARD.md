# PULSE7 Site Standard

This repo follows the locked Hello Texas Records artist site standard.

## Required structure

/images
/artist
/covers
/logos

/audio

index.html
songs.json
latest.json
radio.json
update.bat
STANDARD.md
CNAME

## Locked rules

- Parsons Cross is the structural template.
- Video system is mandatory.
- Every song object contains `"videos": []`.
- If no video exists, show `Video Coming Soon`.
- Do not use Singles, Featured Tracks, or All Tracks.
- Use Album Tracks under each album.
- Use local relative image paths only.

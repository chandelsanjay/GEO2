# WPY Geo‑Map Kiosk — Client Review Pack

**Build:** 2025-09-25 17:54
**Project:** Wildlife Photographer of the Year — Natural History Museum Abu Dhabi

This prototype demonstrates the interactive flow and layout:
- Welcome / Attractor with idle reset
- Category selection (English & Arabic)
- Zoomable world map per category
- Tappable letter markers → Photo detail view

## What to review
1. Overall flow matches storyboard.
2. Touch targets are comfortable on a 75″ screen.
3. Arabic layout (RTL) and labels look correct.
4. Map zoom & pan behaviour is smooth.
5. Idle reset returns to Welcome after 60 seconds.

## Notes
- Content fields (Title, Photographer, Location, Country) are placeholders. Final text will be taken from the museum’s approved WPY panels.
- Map backgrounds are the official Touring Text Panel pages per category.
- Marker positions are configurable in‑app (no coding).

## How to place markers
1. From Welcome, long‑press the top‑left header for 5s (Marker Setup ON).
2. Open a category. Tap a list item (e.g., “A”), then tap the map where “A” appears.
3. Repeat for B, C, D…
4. Use Download marker_positions.json to save, and place it in `/data/` for future runs.


# WPY Geo-Map Kiosk (English / العربية)

A touch-first, offline, kiosk-ready web app for a 75″ touchscreen.
- Welcome/Attractor screen with animated glow
- Category grid (matches WPY panels)
- Zoomable/pannable map per category (official Touring Text Panel pages)
- Tap letter markers to open details (Title, Photographer, Location, Country)
- English ↔ Arabic toggle, RTL layout supported
- No terminal required — just open `index.html`
- Built-in **Setup Mode** to place letter markers (tap-to-set) — no coding

## 1) Run it
1. Open `index.html` in Chrome/Edge.
2. Press **F11** for full screen.

## 2) Add your photo details
- Edit `data/wpy_items.csv` in Excel (or Google Sheets) and fill:
  - `title_en`, `photographer_en`, `location_en`, `country_en`
  - (optional) Arabic columns: `title_ar`, `photographer_ar`, `location_ar`, `country_ar`
- Keep `letter` (A, B, C…) as-is.
- Save, refresh.

## 3) Place the letter markers (Setup Mode)
- From Welcome: **long‑press top‑left of header for 5s** → Setup ON.
- In a category: tap a list item (A, B, C…) then **tap the map**.
- Download `marker_positions.json` and put it into `/data/`.

## 4) Host on GitHub Pages (optional)
1. Create a new repo on GitHub.
2. Upload the **contents of this folder** (not the ZIP) via the web UI (drag & drop).
3. In **Settings → Pages**, set **Branch: `main`** and **Folder: `/ (root)`**.
4. Share the URL with the client.

### Provenance
- Categories and counts: **WPY 61 Light Panels – Categories**. 
- Map images per category: **Touring Text Panel (C01–C17)**.

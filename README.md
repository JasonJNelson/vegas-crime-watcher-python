# Vegas Crime Watcher (Python)

Pure-Python interactive Las Vegas crime map and live-style incident feed.

**Zero external dependencies** — uses only the Python standard library.

## Features

- Interactive dark Leaflet map centered on Las Vegas
- Color-coded markers by crime type
- Filterable crime feed
- Live simulation endpoint (`POST /api/simulate`)
- Login / Subscribe modals (demo)
- Pricing tiers UI
- REST-style API:
  - `GET /` — full web UI
  - `GET /api/crimes` — current crime list (JSON)
  - `POST /api/simulate` — add a new simulated incident
  - `GET /api/health` — health check

## Requirements

- Python 3.9+

## Run

```bash
python app.py
```

Then open **http://127.0.0.1:8080**

## Project layout

```
vegas-crime-watcher-python/
├── app.py          # entire application (data + server + HTML)
├── README.md
└── requirements.txt
```

## Data notes

Incident data is illustrative and drawn from public LVMPD press releases and local reporting (July 2026).  
This is a **demo / educational** project — not an official police product.

Always call **911** for emergencies.

## License

MIT

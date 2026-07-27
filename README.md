# HAR Viewer

A standalone, zero-dependency HAR (HTTP Archive) file viewer. Load a HAR file and inspect every request — headers, bodies, timings, status codes — all in your browser.

![Screenshot](https://img.shields.io/badge/status-stable-green)

## Features

- **Drag & drop** or file picker to load `.har` files
- **Filter by HTTP method** — GET, POST, PUT, PATCH, DELETE, HEAD, OPTIONS
- **Filter by status code** — 2xx, 3xx, 4xx, 5xx
- **Full-text search** across all response bodies
- **Request/response headers** in a sortable table
- **Request/response bodies** with syntax-highlighted JSON
- **Copy as cURL** — single command or with the response body appended
- **Keyboard navigation** — arrow keys to move through entries
- **Persistent history** — previously uploaded files are saved in localStorage (max 5) and shown on refresh
- **Dark theme** — easy on the eyes
- **No build step, no dependencies** — open `index.html` and go

## Usage

1. Open `index.html` in any modern browser
2. Drag a `.har` file onto the drop zone, or click to browse
3. Click any entry in the left panel to inspect it

> **Tip:** Generate a HAR file from Chrome DevTools (`Network` tab → right-click → **Save all as HAR with content**) or Firefox (`Network` tab → **Save All As HAR**).

## File Structure

```
har-viewer/
├── index.html          Main application (HTML + JS)
├── style.css           All styles (dark theme)
└── README.md           This file
```

## License

MIT

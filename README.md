# Aszkenasy & McCarty — authors site

Static multi-page site for **Dr Odet Mark Aszkenasy** and **Dr Moira McCarty**.

## Deploy on Netlify

- **Publish directory:** site root (`.`) — leave blank / set to `/` as appropriate in the UI
- **Build command:** none (leave empty)
- No Node/npm build step required

Connect this repo in Netlify → New site from Git → pick `tedotedo/aszkenasy-mccarty-authors` → deploy.

## GitHub Pages (optional)

Settings → Pages → Source: **Deploy from a branch** → Branch: `main` → Folder: `/ (root)`.

## Pages

| File | Purpose |
|------|---------|
| `index.html` | Home — intro + featured books |
| `books.html` | All books |
| `about.html` | Author bios |
| `assets/styles.css` | Shared stylesheet |
| `assets/covers/` | Cover images |

## Local preview

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8765
# visit http://127.0.0.1:8765/
```

See `DESIGN.md` for layout and palette.

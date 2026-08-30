# Traffic Safety Simulation V2.5.2 Frontend

Static frontend for Cloudflare Pages / GitHub Pages.

## Local run
Use VS Code Live Server or Python:

```bash
python -m http.server 5500
```

Open `http://127.0.0.1:5500`.

## Connect to backend
Edit `config.js`:

```js
window.APP_CONFIG = { API_BASE_URL: 'https://your-render-backend.onrender.com' };
```

Redeploy trigger 08/30/2026 15:44:56

# A.O.W.I Vision — Screenshot-Only (PWA)

This is a fully static, installable web app (PWA). It runs client-side only — no server required.

## Deploy in 60 seconds

### Replit (mobile-friendly)
1. Create a new **HTML/CSS/JS** repl.
2. Upload these four files: `index.html`, `manifest.json`, `sw.js`, and (optional) icons `icon-192.png`, `icon-512.png`.
3. Click **Run** → open the provided public URL.
4. In the browser menu, choose **Add to Home Screen** to install.

### GitHub Pages (permanent URL)
1. Create a new repo and upload these files at the repository root.
2. In repo **Settings → Pages**, set **Source = Deploy from a branch**, **Branch = main / root**.
3. Wait for Pages to build. Your app will be at `https://<user>.github.io/<repo>/`.

### Netlify / Vercel
- Drag-and-drop the folder into Netlify, or `vercel deploy` with a static project — no build step required.

## Using the app
- Tap **Load Demo** to confirm it runs. Then **Upload** your chart screenshots and hit **Analyze**.
- If OCR fails to read the right-side axis, switch **Axis side** to **Left** and re-run.
- The app computes ATR/RSI/MACD/Bollinger from the screenshot and prints A.O.W.I windows + actions.

> No deterministic guarantees: outputs are probabilistic; use risk controls.
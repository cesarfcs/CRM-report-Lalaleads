
# LaLaLeads — Dashboard Analytics CRM

A single‑file web app (HTML + JS + CSS) for analyzing CRM exports (CSV) and generating KPIs and charts.  
No build step needed — just open `index.html` in a browser.

## How to use
1. Open `index.html` in your browser.
2. Enter a client name.
3. Choose your CRM CSV export (headers should include fields like `Campagne`, `Phase du cycle de vie`, `Nom de l'entreprise`, etc.).
4. Click **Analyser les Données CRM** to visualize KPIs and charts.
5. Use **Générer le Rapport PDF** or **Export PowerPoint** to export.

## Deploy on GitHub
### Option A — GitHub Pages (recommended)
1. Push this folder to a new GitHub repository.
2. In Repo **Settings → Pages**, choose **Deploy from branch**, select `main` and `/ (root)`.
3. Your app will be available at `https://<your-username>.github.io/<repo-name>/`.

### Option B — Just host the code
- Upload the files to GitHub; collaborators can clone and open `index.html` locally.

## Files included
- `index.html` — main app (copied from the original file so GitHub Pages serves it by default)
- `crm_analytics_tool (2).html` — original uploaded filename (kept for reference)
- `README.md` — this file

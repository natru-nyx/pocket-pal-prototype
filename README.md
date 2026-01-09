# Pocket Actions Layer (PAL) Prototype

Single-page, front-end only prototype for Pocket’s “Actions Layer,” turning a finished voice recording into structured outputs (Notion, Tasks, Slack, CRM) with mocked AI data.

## Run locally
Open `index.html` in your browser. Dependencies are CDN-only (React 18 UMD, Tailwind via CDN).

## Deploying
### GitHub
1. Initialize and commit:
   ```bash
   git init
   git add index.html README.md vercel.json
   git commit -m "Add PAL prototype"
   ```
2. Create a repo on GitHub (or provide an existing one) and push:
   ```bash
   git remote add origin https://github.com/<your-org>/<repo>.git
   git push -u origin main
   ```

### Vercel (static)
This is a static site; Vercel can deploy it directly from GitHub:
1. Import the GitHub repo in Vercel, select `Framework Preset: Other`.
2. Set:
   - Root directory: `/`
   - Build command: _None_
   - Output directory: `/`
3. Deploy. Vercel will serve `index.html` at the project root.

If you prefer CLI:
```bash
npm i -g vercel
vercel login
vercel --prod
```
Accept defaults; Vercel will detect the static root.

# Central Utah Photography Itinerary

React static site for the Central Utah photography trip itinerary. Built with Vite + React.

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:5173

## Build

```bash
npm run build
```

Output is in the `dist/` folder.

## Deploy to Render with GitHub

1. **Push this folder to a GitHub repo**
   - Create a new repo on GitHub (e.g. `central-utah-itinerary`).
   - From this directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/central-utah-itinerary.git
   git push -u origin main
   ```

2. **Connect to Render**
   - Go to [dashboard.render.com](https://dashboard.render.com).
   - Click **New** → **Static Site**.
   - Connect your GitHub account and select the `central-utah-itinerary` repo.

3. **Configure the static site**
   - **Name:** `central-utah-itinerary` (or any name).
   - **Branch:** `main`.
   - **Build Command:** `npm install && npm run build`
   - **Publish Directory:** `dist`
   - Click **Create Static Site**.

4. Render will build and deploy. Your site will be at `https://central-utah-itinerary.onrender.com` (or the name you chose).

## Optional: `render.yaml`

If you add a Blueprint (e.g. use the included `render.yaml`), Render can create the static site from the repo; otherwise the Dashboard settings above are enough.

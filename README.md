# IRONLINE

A one-screen real-time strategy prototype about keeping an economy flowing while construction drains it.

## Play locally

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173` in a browser.

## GitHub Pages

The repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`. Every push to `main` publishes the root `index.html` to GitHub Pages.

To enable it once in the repository settings:

1. Open **Settings > Pages**.
2. Set **Source** to **GitHub Actions**.
3. Push to `main` or run the **Deploy to GitHub Pages** workflow manually from the **Actions** tab.

The public URL will be:

`https://angelashen233.github.io/Summer-fest-testing-1/`
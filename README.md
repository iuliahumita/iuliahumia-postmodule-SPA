# AI Infrastructure Portfolio Dashboard

GitHub Pages-ready single-page application for a hypothetical $1M AI Infrastructure Quality-Momentum strategy.

## Publish
1. Upload `index.html` to the root of your GitHub repository.
2. Go to Settings -> Pages.
3. Choose Deploy from a branch, `main`, `/(root)`.
4. Save.

The dashboard is intentionally self-contained: CSS, JavaScript and portfolio data are embedded in `index.html`, so it cannot fail because supporting files were omitted.

## Data note
Reference prices are a static snapshot for reliable public demonstration. A production version should fetch market data through a protected backend/serverless endpoint and keep financial-data and LLM API keys off the client.

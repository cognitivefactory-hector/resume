# hector-garza.com

Source for my personal resume site. Deployed on **Cloudflare Pages** — pushes to `main` deploy automatically.

`index.html` is the whole site: self-contained HTML + inline CSS, fonts from Google Fonts via CDN. No build step, no dependencies.

## Editing

All CSS is in a single `<style>` block in the `<head>`. The accent color is `--accent` in the `:root` rule — change it in one place to recolor section rules and headers.

## PDF version

To produce a clean 2-page PDF:

1. Open `index.html` in **Chrome or Edge**.
2. **Ctrl+P** (Cmd+P on Mac) → **Destination:** Save as PDF.
3. **Paper:** Letter · **Margins:** Default.
4. **More settings** → uncheck **Headers and footers**.
5. Save.

> The public site omits a phone number. A private master that includes one (`resume.html`) is kept out of this repo via `.gitignore`.

# giovannigiofre.com

Personal site. Plain static HTML/CSS, no build step.

Single page (`index.html`), Swiss-grid style: Archivo, black / off-white / red.

## Run locally
```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy on Cloudflare Pages
1. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git → pick this repo.
2. Framework preset: **None**. Build command: *(empty)*. Build output directory: `/`.
3. Deploy. You get a `*.pages.dev` URL.
4. After buying the domain on Cloudflare: project → Custom domains → add `giovannigiofre.com` (and `www`, redirected to the apex).

Every push to `main` redeploys.

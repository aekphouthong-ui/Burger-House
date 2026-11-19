# Burger House – Google Sites Embed

## 1. Publish the HTML with GitHub Pages
1. Sign in to https://github.com/
2. Create a new public repository, for example `burger-house`.
3. Upload `index.html` from this folder to the repository root.
4. Open the repository Settings → Pages.
5. Under Build and deployment, choose `Deploy from a branch`.
6. Select branch `main` and folder `/ (root)`, then Save.
7. Wait for GitHub Pages to publish the site. The public URL will look like:
   `https://YOUR-USERNAME.github.io/burger-house/`

## 2. Embed it in Google Sites
1. Open https://sites.google.com/ and edit your Google Site.
2. Choose Insert → Embed → By URL.
3. Paste the GitHub Pages URL.
4. Click Insert, resize the embedded frame, and Publish the Google Site.

## Important notes
- The original HTML, CSS, and JavaScript are preserved in `index.html`.
- The cart, ingredient selection, quantity controls, and price calculations work in the hosted HTML page.
- The existing checkout is a demonstration only: it does not send orders to a restaurant or save them to a database.
- To receive real orders, connect a backend or a form/order service later.
- The Google Sites page embeds the hosted page; it does not directly host or execute the raw HTML file.

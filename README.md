# share

Source for [yairmau.com/share](https://yairmau.com/share): a landing page linking to things I want to share with friends and family.

Built with Jekyll, which GitHub Pages runs automatically. There is no build step to run.

## Adding a page

1. Create a folder named after the page's URL, e.g. `my-page/`.
2. Inside it, add `index.md` starting with:

   ```yaml
   ---
   title: My page title
   date: 2026-11-07
   share: true
   summary: One sentence shown on the landing page.
   ---
   ```

3. Write the page in Markdown below that. Commit and push.

Pages with `share: true` appear on the landing page, newest first. Leave it out (or set `false`) to publish a page by link only, without listing it.

## Setup (once)

In the repo on GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`**.

If yairmau.com is served by GitHub Pages from your user site repository (`yairmau.github.io`) with a custom domain, this repo appears at `yairmau.com/share` automatically. No CNAME file is needed here.

## Search engines

`noindex: true` in `_config.yml` asks search engines not to index these pages. The pages are still public to anyone with the link.

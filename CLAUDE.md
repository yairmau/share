# CLAUDE.md

This repo is the source for **yairmau.com/share**: Yair Mau's pages for friends and family. It's a Jekyll site built by GitHub Pages from `main` (root). Pushing to `main` publishes, so there is no build step and nothing to deploy.

## Before pushing

- **Everything here is public.** Anyone with the link can read the site and this repo's source. Do not add private family details, contact info, or anything Yair hasn't clearly asked to publish.
- **Show Yair the finished page and get his OK before pushing.** A push is a publish.
- Write commit messages in plain English, e.g. `Add page: <title>`.

## Adding a page

1. Pick a short, lowercase, hyphenated slug. Make a folder with that name containing `index.md`. The page will live at `yairmau.com/share/<slug>/`.
2. Start the file with front matter:

   ```yaml
   ---
   title: Page title
   date: YYYY-MM-DD        # publish date; the landing page sorts by this, newest first
   share: true             # list on the landing page; omit to publish by link only
   summary: One sentence shown under the title on the landing page.
   ---
   ```

3. Write the body in Markdown (GitHub-flavored: tables, fenced code blocks).
   - Don't repeat the title as an `# H1`. The layout prints the title and date.
   - Use `##` for sections.
   - Code blocks get a Copy button automatically. Use them for text readers are meant to copy.
   - End with a `## Sources` list of links when the page draws on outside material.
4. If the source is a Claude doc or other artifact, export it to Markdown and convert it. Drop its byline/date line, since the front matter replaces it.

## Files

| Path | Purpose |
| --- | --- |
| `_config.yml` | Site settings. `baseurl: /share` must stay. `noindex: true` asks search engines not to index |
| `_layouts/default.html` | The single layout: header, article, footer, copy-button script |
| `assets/style.css` | All styling (light and dark mode) |
| `index.md` | Landing page. Lists every page with `share: true`, newest first |
| `<slug>/index.md` | One shared page each |

## Conventions

- Keep the site simple: no themes, plugins, or JavaScript frameworks. GitHub Pages only supports its own whitelisted Jekyll plugins.
- Links inside the site use `{{ '/path/' | relative_url }}` so the `/share` prefix is kept.
- Don't edit the layout or styles unless asked. New pages should look like the existing ones.
- Jekyll may not be installable locally. If you can't build, check the Markdown and front matter carefully, and tell Yair the page is unverified until he sees it live.

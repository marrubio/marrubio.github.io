# marrubio.github.io
GitHub Pages site for the Marrubio portfolio.

## Portfolio structure

- `index.md`: landing page with the hero, services grid, project teasers, and CTA to the key sections.
- `about.md`, `projects.md`, `contact.md`: dedicated routes that describe who you are, highlight featured work, and share contact methods.
- `_config.yml`: applies the `jekyll-theme-minimal`, metadata, and the navigation menu rendered site-wide.

## Deployment reminders

1. Make sure the branch selected under the **Pages** tab in GitHub is the one you want as the live site (typically `main`).
2. Update Markdown or asset files, then run `git add`, `git commit`, and `git push`.
3. GitHub rebuilds the site automatically; the final URL is listed in the same **Pages** tab (https://marrubio.github.io by default).

## How to customize further

- Edit the Markdown content to keep copy and project details current.
- Embed CSS with `<style>` blocks or add an `assets/` folder if you need more sophisticated styling.
- To replace the layout entirely, add a `_layouts/custom.html` file and switch `layout: default` to `layout: custom` inside the front matter.

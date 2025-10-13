
## Structure

- `_config.yml` — main Jekyll config
- `_posts/` — blog posts
- `_layouts/` — templates
- `_includes/` — partial templates
- `_site/` — generated site (ignored in Git)
- `assets/` — images, CSS, JS
- `index.md` or `index.html` — homepage

## Development

1. Install Ruby and Jekyll
2. Run locally:

   ```bash
   bundle exec jekyll serve
   ```

   Access locally at: http://127.0.0.1:4000

3. Build manually:

    bundle exec jekyll build

## GitHub Pages

    The main branch contains the source files.

    _site/ is ignored. GitHub automatically builds the site.

    Published at: https://jrushworth.github.io

## Useful Commands

    Check status: git status

    Add changes: git add .

    Commit changes: git commit -m "Message"

    Push to GitHub: git push origin main

    Pull updates from remote: git pull origin main --allow-unrelated-histories

# Personal website starter for HugoBlox Academic CV

This starter pack is meant to be copied into a repo created from the official HugoBlox Academic CV template.

## Recommended path
1. Create a new GitHub repo from the official template:
   https://github.com/HugoBlox/hugo-theme-academic-cv
2. Copy the files from this starter pack into that repo, replacing files when prompted.
3. Edit the placeholder content in:
   - `content/authors/admin/_index.md`
   - `content/_index.md`
   - `content/projects/...`
   - `content/blog/...`
   - `config/_default/menus.yaml`
   - `config/_default/params.yaml`
4. Add your headshot as `assets/media/avatar.jpg` (or update the filename in your profile if needed).
5. Commit and push to GitHub.

## Suggested homepage layout
- Hero: name, short positioning statement, two primary links
- About: concise 3–4 sentence intro
- Selected Work: 3 featured projects
- Writing: latest posts
- Contact / links: email + GitHub + LinkedIn

## Google Sites -> GitHub Pages redirect
Google Sites does not offer a true server-side 301 redirect. The cleanest route is:
1. Use a custom domain (for example, `yourname.com`)
2. Point that domain to GitHub Pages
3. Update Google Sites to link visitors to the new domain, or place a clear move notice on the old site

If your old Google Site is on a custom domain already, move that domain to GitHub Pages and keep the old Google Sites URL as a fallback notice page.

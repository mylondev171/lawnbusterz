These guide pages are kept in the repo and excluded from the Vercel deploy
by .vercelignore, so their old /guides/<slug> URLs 404 in production.

To publish one again:
1. Move its folder from _drafts/guides/<slug> back to guides/<slug>.
2. Add it to guides/index.html, sitemap.xml, and llms.txt.
3. Add it to the Guides dropdown and the footer Guides column.
4. Remove _drafts from being the only copy, then redeploy.

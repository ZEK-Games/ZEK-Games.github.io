# ZEK Games website

Static website hosted on GitHub Pages at https://zek-games.github.io/.
No build step, JavaScript dependencies, external fonts or website analytics.

## Files

- `index.html`: studio home, four game links and support contact.
- `assets/css/site.css`: original responsive styles shared by both pages.
- `privacy.html` and `privacy/index.html`: identical privacy policy, retaining both existing URL forms. Update both together.
- `app-ads.txt`: existing publisher file, preserved.
- `robots.txt` and `sitemap.xml`: public crawler information.

Preview with `python3 -m http.server 8765`, then visit http://localhost:8765/.
GitHub Pages publishes the repository's configured source branch. There are no paid hosting services.

The previous BootstrapMade template and bundled vendor assets remain in repository history and in unused asset directories; the current pages use the new `site.css` stylesheet and do not load that template. `Readme.txt` preserves the old template's provenance. Game artwork belongs to the existing ZEK Games projects.

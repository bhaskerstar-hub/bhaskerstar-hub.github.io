# bhaskerstar-hub.github.io

Developer site for Bhasker Chaurasia — served at <https://bhaskerstar-hub.github.io/>.

Static HTML and one stylesheet, no build step and no dependencies. Edit a file, commit,
push, and GitHub Pages redeploys within a minute or so.

| File | Purpose |
|------|---------|
| `index.html` | Home — published apps, open-source projects, contact |
| `support.html` | Per-app support routes and what to include in a report |
| `privacy.html` | Site privacy statement plus an index of per-app policies |
| `404.html` | Not-found page |
| `style.css` | Shared styles, light and dark |
| `robots.txt`, `sitemap.xml` | Search engine basics |

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Related sites

- DocAura — <https://bhaskerstar-hub.github.io/docaura/> (repo `bhaskerstar-hub/docaura`)
- PhotoPorter — <https://bhaskerstar-hub.github.io/photoporter-legal/> (repo `bhaskerstar-hub/photoporter-legal`)

Those repos hold each app's own privacy policy, which is the URL registered with Apple.
Update them in place — don't move those URLs.

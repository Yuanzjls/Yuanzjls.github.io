# Scott's Blog

Bilingual personal blog at <https://yuanzjls.github.io>, built with Hugo and hosted free on GitHub Pages.

## Writing

Use [Pages CMS](https://app.pagescms.org) in a browser, or add Markdown files directly:

- Chinese posts: `content/zh/posts/` (served from the site root)
- English posts: `content/en/posts/` (served under `/en/`)
- Images: `static/images/`, referenced as `/images/name.png`

To link the two language versions of a post, give both the same `translationKey`.

Every push to `main` builds and deploys the site through `.github/workflows/hugo.yml`.

## Local preview

Install [Hugo Extended](https://github.com/gohugoio/hugo/releases) 0.169.0 or newer, then run:

```bash
hugo server
```

Open <http://localhost:1313>.

## Theme

`themes/PaperMod` is a copy of [hugo-PaperMod](https://github.com/adityatelange/hugo-PaperMod) at commit `118119693d8b5ac211b939775678310973bcb232`, not a submodule. To update it, replace the folder with a newer version.

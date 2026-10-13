# critiqueofaiconstitution.info

Static site served by GitHub Pages (Jekyll builds it automatically; no build step needed).

## Where to edit content

| Page | File |
|---|---|
| Overview (home) | `index.md` |
| About Us | `about.md` |
| Section 1–7 | `_sections/section-1.md` … `_sections/section-7.md` |

Each file starts with a short block between `---` lines (title, order, optional summary). Edit the title there to rename a page and its navigation entry; everything below is Markdown. The nav and the section list on the Overview page update automatically.

## Publishing

1. Push to `main` at https://github.com/clr/critiqueofaiconstitution.info
2. Repo **Settings → Pages → Build and deployment**: Source "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Under **Custom domain** enter `critiqueofaiconstitution.info` (the `CNAME` file already contains it) and tick **Enforce HTTPS** once the certificate is issued.
4. DNS at your registrar: for the apex domain add four `A` records pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` (optionally matching `AAAA` records and a `www` CNAME to `clr.github.io`).

## Preview locally (optional)

```
bundle install
bundle exec jekyll serve
```

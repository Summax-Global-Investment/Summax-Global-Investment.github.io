# Summax Global Investment — website

The public website for Summax Global Investment.

**Live at: https://summax-global-investment.github.io/**

## What this repository is

This is the organisation Pages site for the Summax-Global-Investment GitHub
organisation, so GitHub Pages publishes it from the **root of the `main`
branch**. The repository therefore holds the built site: the HTML, CSS, images
and scripts that visitors receive.

## Pages

| Page | File |
| --- | --- |
| Home | `index.html` |
| Projects | `projects.html` |
| About | `about.html` |

## Editing the site

The site is written in [Quarto](https://quarto.org) and the source files
(`index.qmd`, `about.qmd`, `projects.qmd`, `_quarto.yml`, `styles.css`) live in
a separate repository. The rendered output is copied into this repository.

Because Pages publishes the root, any edit here takes effect on the live site
as soon as it is committed to `main`.

## Notes

- `.nojekyll` is present, so GitHub serves the files exactly as built.
- All asset paths in the build are relative, so the site works unchanged at the
  organisation root.

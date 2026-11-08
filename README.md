# SAF-T API site

Public landing page for the SAF-T (PT) validator API. The site is static HTML: a bilingual product page, plus privacy and terms templates in Portuguese and English.

After GitHub Pages is enabled for this repository with the source set to GitHub Actions, the site is published at:

https://pedrommcustodio.github.io/saft-api-site/

| Page | File |
| --- | --- |
| Landing | `index.html` |
| Privacidade | `privacidade.html` |
| Privacy | `privacy.html` |
| Termos | `termos.html` |
| Terms | `terms.html` |

Links between these pages are relative, so they resolve under `/saft-api-site/`.

A push to `main` runs [`.github/workflows/pages.yml`](.github/workflows/pages.yml). That workflow uploads the repository root with `actions/upload-pages-artifact` (including `.nojekyll`) and publishes it with `actions/deploy-pages`.

This repository holds the public site.

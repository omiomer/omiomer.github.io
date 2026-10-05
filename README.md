# omiomer.github.io

Personal academic website of Ömer Ekmekcioğlu — https://omiomer.github.io

Built with [al-folio](https://github.com/alshedivat/al-folio) v1.2 (Jekyll). Pushing to `main`
triggers `.github/workflows/deploy.yml`, which builds the site into the `gh-pages` branch.

## Where things live

| To change | Edit |
|---|---|
| Bio, job market paper blurb, news, references | `_pages/about.md` |
| Papers (grouped by the `keywords` field: `jmp`, `working`, `wip`, `refereed`) | `_bibliography/papers.bib` |
| Teaching | `_pages/teaching.md` |
| CV | replace `assets/pdf/CV_Omer_Ekmekcioglu.pdf` |
| Photo | add the new photo to `assets/img/` under a **new** filename and point `profile.image` in `_pages/about.md` at it (reusing a filename lets browsers keep showing the cached old photo) |
| Social links | `_data/socials.yml` |
| Name, description, search keywords | `_config.yml` |

## Local preview

```bash
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

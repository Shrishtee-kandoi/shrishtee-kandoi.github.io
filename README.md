# shrishtee-kandoi.github.io

Personal website, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll template (v1.2).

## Edit

- Bio, photo, and home-page layout: `_pages/about.md` (photo is `assets/img/prof_pic.jpg`)
- Publications: `_bibliography/papers.bib` (`selected = {true}` shows a paper on the home page)
- CV: replace `assets/pdf/ShrishteeKandoi_resume.pdf`
- Social links: `_data/socials.yml`
- Name, description, and site-wide settings: `_config.yml`
- News items go in `_news/`, projects in `_projects/` (add `_pages/news.md` / `_pages/projects.md` from the al-folio repo to put them in the navbar)

## Preview locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/.

## Deploy

Pushing to `master` runs `.github/workflows/deploy.yml`, which builds the site into the `gh-pages` branch. In the repo settings, Pages must serve from the `gh-pages` branch.

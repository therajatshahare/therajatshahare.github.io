# Rajat Shahare: Academic & Professional Portfolio

**Live site: [therajatshahare.github.io](https://therajatshahare.github.io)**

The personal portfolio of Rajat Shahare, Ph.D. Research Scholar in English at Rashtrasant Tukadoji Maharaj Nagpur University. It covers research on Colson Whitehead and African American literature, publications, teaching and open-source projects.

Built with [Jekyll](https://jekyllrb.com) and hosted on [GitHub Pages](https://pages.github.com). The design is inspired by jekyllrb.com.

## Pages

| Page | File |
|---|---|
| Home | `index.html` |
| About | `about.md` |
| Education | `education.md` |
| Research | `research.md` |
| Publications | `publications.md` |
| Teaching | `teaching.md` |
| Projects | `projects.md` |
| Academic Activity | `academic-activity.md` |
| Contact | `contact.md` |

## Structure

```
_config.yml        Site settings, navigation and profile links
_layouts/          default.html (base) and page.html (inner pages)
assets/css/        style.css
assets/img/        Profile photo
assets/icons/      Social media icons
assets/cv/         CV (PDF) used by the Download CV button
*.md, index.html   Page content
```

## Run locally

Requires Ruby and Bundler.

```
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Editing

- Page text lives in the `.md` files, in Markdown with a little HTML.
- The menu order is set under `nav:` in `_config.yml`.
- Profile links (GitHub, LinkedIn, ORCID, Telegram) are set under `author:` in `_config.yml`.
- The Download CV button expects `assets/cv/Rajat-Shahare-CV.pdf`.

Pushing to `main` redeploys the site automatically.

## License

Site code (layouts, styles, configuration) is released under the [MIT License](LICENSE).
All text, research, publication details and photographs are © Rajat Shahare and are not licensed for reuse.

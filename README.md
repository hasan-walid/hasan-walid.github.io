# Personal site — Jon Barron style (GitHub Pages)

This repo hosts my personal site, built as a minimal single page inspired by [jonbarron.github.io].

## Getting started
1) Create a public repo named `<your-username>.github.io`.
2) Add the files from this folder to the repo and commit.
3) Visit `https://<your-username>.github.io` after a minute or two.

## Customize
- Edit `_config.yml` for name, bio line, email, CV link, and socials.
- Replace `images/profile.jpg` and `files/CV.pdf` with your own.
- Add or edit articles in `data/writings.yml` — they show up automatically on the homepage.

## Custom domain (optional)
- Add a `CNAME` file with your domain (e.g., `example.com`).
- Point your DNS `CNAME` record to `<your-username>.github.io`.

## Local preview (optional)
If you want to test locally, install Ruby + Jekyll, then:
```bash
bundle exec jekyll serve
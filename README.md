# Personal Portfolio

Personal portfolio website built with Jekyll and the Minimal Mistakes theme.

Live site: [hylin0517.github.io](https://hylin0517.github.io)

## Overview

This repository contains my personal website, including:

- homepage and background information
- project portfolio pages
- resume page
- custom styling and theme overrides

The site is used to showcase my work in data science, analytics, machine learning, forecasting, and experimentation.

## Tech Stack

- Jekyll
- Minimal Mistakes
- SCSS
- GitHub Pages

## Repository Structure

- `index.html` - homepage content
- `_pages/projects.md` - main projects index page
- `_pages/resume.md` - resume page
- `projects/` - individual project writeups
- `assets/css/main.scss` - custom styling
- `_config.yml` - Jekyll site configuration

## Local Development

Install dependencies and run the site locally from the repo root:

```bash
bundle install
bundle exec jekyll serve
```

Then open:

```text
http://127.0.0.1:4000
```

## Notes

- Changes to `_config.yml` require restarting the local Jekyll server.
- Content pages are written in Markdown and HTML.
- Styling overrides live in `assets/css/main.scss`.

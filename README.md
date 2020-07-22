# Science and Us

Welome to the repository for the [Science and Us](https://scienceandus.org) website!

The website is built using [Jekyll](https://jekyllrb.com/) (a static site generator) and hosted by [Netlify](https://www.netlify.com/). It uses [Forestry](https://www.forestry.io/) as a content management system.

**Most edits to the website content (images, pages, team members, etc.) should be made using the CMS, not directly to the source code here.**

## Organization

- `assets/` contains all images and videos.
- `styles/` contains the files used to style website, written in [SCSS](https://sass-lang.com/) that gets compiled to regular CSS by Jekyll.
- `pages/` contains all the pages of the website, usually as Markdown (`.md`) files editable via Forestry CMS.
- `_redirects` tells Netlify to redirect certain pages of the website to other URLs (internal or external).

### Jekyll-Related

- `_config.yml` defines variables used across the website, as well as configuration settings.
- `_includes/` contains snippets of HTML that are used multiple times across the website. They're extracted to a file in this folder to avoid unnecessary repetition and make it easier to change things across the website.
- `_layouts/` are templates for types of pages.

### Deployment-Related

`Gemfile`, `Gemfile.lock`, `.ruby-version` tell Netlify what version of Ruby and what Jekyll packages are used.

## Installation

To test/run the website on your local machine, you must have Jekyll installed (see [instructions](https://jekyllrb.com/docs/installation/)). Then run the following commands in a terminal:


```
git clone https://github.com/scienceandus/scienceandus.github.io

cd scienceandus.github.io

jekyll serve
```

# Queens' Computer Science Society

The Queens' Computer Science Society website, built with [Eleventy](https://www.11ty.dev/).

## Installation

Install `npm` and clone the git repo.

```bash
npm install
npm run serve   # start dev server with live reload
npm run build   # build to _site/
```

## Project Structure

All content is under `src/`

- `_data/`: site-wide data
- `_includes/`: layouts
- `css/`: stylesheet, passed through as-is to `_site/`
- `img/`: images, passed through as-is to `_site/`

Everything else is either `.html` or `.md` files to be served

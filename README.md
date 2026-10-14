# Yujian Zhang · Personal Website

Source for [zhangyj720.netlify.app](https://zhangyj720.netlify.app/), built with [Hugo Blox](https://hugoblox.com/) and deployed by Netlify.

## Updating the site

- Biography, education, experience, and selected publications: `content/authors/admin/_index.md`
- Homepage layout and resume button: `content/_index.md`
- Downloadable resume: `static/uploads/resume.pdf`
- Site title, navigation, and metadata: `config/_default/`

Netlify builds the `main` branch with Hugo 0.126.3, as configured in `netlify.toml`.

## Local build

Install Hugo Extended 0.126.3, then run:

```sh
hugo --gc --minify
```

The Hugo Blox components and license details are retained in this repository.

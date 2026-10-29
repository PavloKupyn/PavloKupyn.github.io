# PavloKupyn.github.io

My personal website, built with [Hugo](https://gohugo.io) and the [Noesis](https://github.com/josephhutch/noesis) theme.

## Local development

```sh
git clone --recurse-submodules git@github.com:PavloKupyn/PavloKupyn.github.io.git
hugo server        # http://localhost:1313
```

## Writing

```sh
hugo new posts/my-post/index.md   # then set draft: false
```

- Site settings and social links: `hugo.toml`
- Home page text and profile: `content/_index.md`
- About page: `content/about/index.md`
- Favicons: `static/`
- Custom CSS: `assets/css/override.css`

## Deploy

Pushing to `main` builds and publishes the site via GitHub Actions (`.github/workflows/hugo.yml`).
Set **Settings → Pages → Source** to **GitHub Actions** once.

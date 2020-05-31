# 🚧 WIP - CodeJam 2020 Website

This is the website for McGill CodeJam.(2020), [deployed to Netlify](https://codejam2020.netlify.app).

The `hugo` base theme is [Hero](https://themes.gohugo.io/hugo-hero-theme).

## Getting Started

Install `hugo` following [the instructions here](https://gohugo.io/getting-started/installing/) _or_ use Go 11+:

```bash
$ go get github.com/gohugoio/hugo
$ go install github.com/gohugoio/hugo
```

### Hugo Version

Ensure that your version of `hugo` is >= `0.51`:

```bash
$ hugo version
Hugo Static Site Generator v0.72.0-DEV linux/amd64 BuildDate: unknown
```

This is **important** because the specified theme only runs on the extended version of `hugo`!

### Local Deploy

To get started, type the following and view your site at `localhost:1313`:

```bash
$ hugo server
```

If you're playing around with themes or configs, use:

```bash
$ hugo server \
--source . \
--config config.toml \
--themesDir themes \
--theme hugo-hero-theme
```

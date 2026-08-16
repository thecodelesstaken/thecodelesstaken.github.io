# The Code Less Taken

The Hugo source for [thecodelesstaken.com](https://thecodelesstaken.com), an independent technical publication that tests overlooked computing ideas against current engineering problems.

## Local development

Hugo Extended 0.146 or later is recommended.

```sh
hugo server
```

The production build is:

```sh
hugo --gc --minify
```

The site uses a custom theme with no third-party front-end dependencies, hosted fonts, trackers, or required client-side framework. The small inline script only manages the reader's color-mode preference. Discovery assets include RSS, an XML sitemap, `robots.txt`, `llms.txt`, JSON-LD, and a social preview image.

## Publishing

Pushes to `main` are built and deployed through GitHub Pages. The canonical domain is configured in `static/CNAME`.

## Licensing

The website source code is MIT licensed. Editorial content and original brand assets remain copyright The Code Less Taken. See [LICENSE](LICENSE).

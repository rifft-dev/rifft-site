# rifft-site

Marketing website for [Rifft](https://rifft.dev) — open-source multi-agent AI debugger.

## Structure

```
rifft-site/
├── index.html   # single-page marketing site
├── og.png       # 1200×630 Open Graph image
└── robots.txt   # search engine directives
```

## Deployment

The site is deployed via Cloudflare Pages from this repository. Every push to `main` triggers an automatic deployment to [rifft.dev](https://rifft.dev).

No build step. No framework. Static HTML only.

## Editing

Edit `index.html` directly. The entire site — styles, content, and layout — is self-contained in that one file.

To update the OG image, replace `og.png` with a new 1200×630px PNG.

## Related

- **Product repo**: [rifft-dev/rifft](https://github.com/rifft-dev/rifft) — the open-source debugger itself
- **Docs**: [github.com/rifft-dev/rifft/blob/main/README.md](https://github.com/rifft-dev/rifft/blob/main/README.md)
- **Contact**: hello@rifft.dev

# wait-for-languages

Static signup site for **Mr. Jay's Language Learning Tips** — a free weekly practical language-learning tip newsletter by Mr. Jay, an English teacher in Korea.

Hosted on [GitHub Pages](https://mrjkorea.github.io/wait-for-languages/) from the root of the `main` branch (project site under `/wait-for-languages/`).

## What's here

| Path | Purpose |
|------|---------|
| `index.html` | Main signup landing page |
| `sample/` | Sample newsletter issue (HTML) |
| `go/*/` | Short links with UTM tags for social channels |
| `css/styles.css` | Shared styles (mobile-first) |
| `assets/favicon.svg` | Logo / favicon mark (MJ speech bubble) |
| `sitemap.xml`, `robots.txt` | SEO |
| `.nojekyll` | Disable Jekyll processing on GitHub Pages |

Signup uses a prominent link to the public Kit page: [wait-for-languages.kit.com](https://wait-for-languages.kit.com/). UTM parameters on the landing URL are appended to that link automatically.

## Short links

See [go/README.md](go/README.md) for the full list of trackable short URLs (Instagram, TikTok, YouTube, Naver, Cafe, Reddit, X, Threads, Pinterest, Other).

## Local preview

From the repo root:

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080/` (or the project path if you serve from a parent directory).

## Brand

Public newsletter name: **Mr. Jay's Language Learning Tips**. Keep retired newsletter names out of site copy.

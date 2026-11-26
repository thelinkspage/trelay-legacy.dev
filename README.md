> [!IMPORTANT]
> **This is the legacy Trelay codebase.** Trelay is being succeeded by **[thelinks.page](https://thelinks.page)**, an open-source (AGPL-3.0) rewrite that combines link-in-bio pages with a full URL toolkit. Development continues at **[thelinkspage/thelinks](https://github.com/thelinkspage/thelinks)**, which will ship a Trelay importer. This repo is kept as a reference implementation and will be archived once the importer lands.

<p align="center">
  <img src="static/logo.png" alt="Trelay" width="80" />
</p>

<h1 align="center">Trelay</h1>

<p align="center"><strong>Your Links, Your Server.</strong></p>

This repo is the marketing site and docs for **Trelay**, the self-hosted URL manager. The app itself lives at [github.com/thelinkspage/trelay-legacy](https://github.com/thelinkspage/trelay-legacy).

## Why Trelay?

- **Self-hosted**: data stays on your box
- **Privacy-minded**: no vendor analytics in the product; IP anonymization by default
- **Built for operators**: CLI, HTTP API, and a real dashboard
- **One container** to run in production
- **MIT license**

## Features (high level)

- Custom slugs, passwords, expiry, one-time links
- Folders, trash, restore
- Click stats with CSV/JSON export
- Open Graph previews, QR codes
- CLI with completion; REST API and OpenAPI spec in the main repo

## Quick start (clone the app)

```bash
git clone https://github.com/thelinkspage/trelay-legacy.git && cd trelay-legacy
cp env.example .env   # set API_KEY, JWT_SECRET
docker compose up -d
# Dashboard: http://localhost:8080
```

## Links

- **App source**: [github.com/thelinkspage/trelay-legacy](https://github.com/thelinkspage/trelay-legacy)
- **README / setup**: [github.com/thelinkspage/trelay-legacy#readme](https://github.com/thelinkspage/trelay-legacy#readme)

## License

MIT

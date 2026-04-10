# Affinity Hospitality

Official source for the Affinity Hospitality UAE marketing site.

This repository contains a static, performance-focused website for a B2B hospitality linen manufacturer and supplier serving the UAE, GCC, and Africa. The site is built around a single `index.html` entry point with local assets and Tailwind CSS for styling.

## Stack

- HTML
- Tailwind CSS
- Local fonts, images, and audio assets
- `pnpm` for CSS build scripts

## Project Structure

```text
.
|-- index.html
|-- assets/
|   |-- css/
|   |-- fonts/
|   |-- images/
|   `-- audio/
|-- _headers
|-- .htaccess
`-- package.json
```

## Local Development

Install dependencies:

```bash
pnpm install
```

Rebuild Tailwind CSS:

```bash
pnpm run build:css
```

Watch Tailwind CSS while editing:

```bash
pnpm run watch:css
```

To preview locally, serve the project root with any static file server.

## Notes

- Production assets are committed to the repository.
- Hosting-specific files such as `_headers` and `.htaccess` are included.
- This repository is intentionally minimal and does not include a frontend framework or backend service.

## License

This project is proprietary and not licensed for public reuse. See [LICENSE](LICENSE).

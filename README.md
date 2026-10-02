# validate.al docs

Source of [docs.validate.al](https://docs.validate.al), published by Mintlify from the `main` branch.

| Path | Content |
|---|---|
| `index.mdx` | Docs home: the list of validate.al products |
| `email-validation/` | Email Validation guides |
| `api-reference/` | API reference; endpoint pages are generated from `email-validation.yaml` (OpenAPI) |
| `docs.json` | Site config: navigation, colours, logo, navbar |

Add a product by creating its folder, adding a group in `docs.json`, and a card in `index.mdx`.

## Preview locally

```bash
npm i -g mint
mint dev          # http://localhost:3000
mint broken-links # check internal links
```

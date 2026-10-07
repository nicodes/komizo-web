# komizo website

Static Astro landing page for [komizo](https://komizo.dev).

Primary destination: [komizo](https://github.com/nicodes/komizo#readme).

The current product is a CLI and local UI for preparing and operating app-scoped Compose hosts over SSH. There is no hosted account.

## Development

Use the Bun version in `.mise.toml`.

```sh
bun install --frozen-lockfile
bun run dev
bun run build
bun run preview
```

Run `bun run typecheck` before building.

The site is static and ships no client-side JavaScript. Existing CI validates the build and product-specific output contract.

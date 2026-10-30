<!-- Generated from private documentation source. Do not edit directly. Source SHA256: 6f3c6b3783e7973b91a480438765f2617bb75011421305461d9d64b3b47b6c92 -->

# komizo-web

Static website built with Astro.

Install the [komizo release](https://github.com/nicodes/komizo#install) matching `komizo.lock`, then run:

```sh
komizo dev                 # Foreground development server
komizo check               # Complete applicable source, build and output checks
komizo run build           # Generate dist/
komizo describe            # Inspect tools and available commands
```

Ctrl-C stops development. This website needs no runtime credentials or credential `.env` file.

## Install the CLI

With curl:

```sh
curl -fsSL https://komizo.dev/install | sh
```

Or with mise:

```sh
mise use --global github:nicodes/komizo@latest
```

An icon-only copy control sits on the right inside each install-command outline and shows a checkmark after copying. If clipboard access is unavailable, the command remains selectable for manual copying.

The curl installer requires an authenticated GitHub CLI session for release provenance verification. See [komizo](https://github.com/nicodes/komizo#readme) for setup and installation options.

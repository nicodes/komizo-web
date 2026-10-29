<!-- Generated from private documentation source. Do not edit directly. Source SHA256: 94431c521d9e28408edec51b585d058ffa11083547ac648f442314a8f943fc3b -->

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

Each install command has a Copy button with confirmation. If clipboard access is unavailable, the command remains selectable for manual copying.

The curl installer requires an authenticated GitHub CLI session for release provenance verification. See [komizo](https://github.com/nicodes/komizo#readme) for setup and installation options.

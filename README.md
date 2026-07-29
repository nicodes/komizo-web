# komizo-web

The splash page at [komizo.dev](https://komizo.dev). One static page.

```sh
mise install
bun install
bun run dev      # http://localhost:4321
bun run build    # -> dist/
```

## What is here

```
src/layouts/Full.astro   <head>, meta, structured data
src/pages/index.astro    the page, and its styles
src/styles/global.css    palette, fonts, resets
```

Plain Astro with scoped CSS. No component framework and no CSS framework: this
is one page with no interactivity, and the scaffold's Qwik and Tailwind were a
runtime and a build step to produce markup that is written out directly.
Removing them is why the built page ships **no JavaScript at all**.

## The interface on the page is text

The terminal mockup in the hero is markup, not a screenshot. It stays
selectable, it scales with the reader's font size, and it never renders blurry
on a display it was not captured for.

The palette is the CLI's own — komizo picks colours per terminal background, and
`#0B7285` is its accent on a light one. The site wears what the product wears
rather than inventing a brand alongside it.

## Related

- [komizo-cli](https://github.com/nicodes/komizo-cli) — the CLI
- [komizo-actions](https://github.com/nicodes/komizo-actions) — the GitHub Actions
- [komizo](https://github.com/nicodes/komizo-be) — the docs

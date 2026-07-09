# Studio Wren — Showcase Site

Studio showcase concept: an editorial portfolio site for an interior design studio (private residential + boutique hospitality). Not a live client.

- **Live:** https://studio-wren.vercel.app (project pending rename from default "site")
- **Stack:** Single-file static site (`index.html`) — HTML, CSS, and JS inline. No build step.
- **Style archetype:** B — Editorial Gallery (reference: ol.studio; see studio design playbook)
- **Deploy:** Vercel, static. Push to `main` auto-deploys.

## Local preview

```
npx serve .
```

## Editing

Everything lives in `index.html`. Design tokens (palette, type scale) are CSS variables at the top of the inline stylesheet.

# Teral website

The Astro website for [Teral](https://github.com/zuhaibullahbaig/teral), a native Rust and GTK4 file manager for modern Linux desktops.

## Run locally with Bun

```bash
bun install
bun run dev
```

Astro will print the local URL, normally <http://localhost:4321>.

## Production build

```bash
bun run build
bun run preview
```

The static site is generated in `dist/`.

## Deploy to Vercel

1. Push this directory to its own Git repository.
2. Import the repository into Vercel.
3. Vercel will detect Astro automatically.
4. Use `bun run build` as the build command and `dist` as the output directory if Vercel does not fill them automatically.
5. Add the chosen domain in the Vercel project settings.

No environment variables or server functions are required.

## Updating a release

Change `version` in `src/data/project.ts`. Download buttons continue to use GitHub's `/releases/latest` URL automatically.

## Images

Product screenshots live in `public/images/`. They are displayed at their complete native aspect ratio and are never cropped.

## License

MIT. Copyright © 2026 Zuhaib Ullah Baig.

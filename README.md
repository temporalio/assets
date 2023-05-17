Files hosted by Vercel at `assets.temporal.io`. Published on merges to `main`.

- A file added to `files/foo.jpg` will appear at `assets.temporal.io/foo.jpg` and use Vercel's [default CDN policy](https://vercel.com/docs/concepts/edge-network/caching#static-files-caching) (not cached / `max-age=0`).
- A file added to `files/w/bar.png` will appear at `assets.temporal.io/w/bar.png` and be cached by user's browsers for a week.
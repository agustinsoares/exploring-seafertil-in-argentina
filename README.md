# Exploring Seafertil in Argentina

A one-page market exploration and collaboration proposal from Dolores Rivera to the Seafertil team.

It is a plain static site: `index.html` plus the `media/` folder. There is no build step.

## Deploy on Vercel

1. Import this repository in Vercel.
2. Framework preset: **Other**. Leave the build command and output directory empty.
3. Deploy. Vercel serves `index.html` from the root.

## Editing

- Text: edit `index.html`. Each section is a `<section>` with an id (`about`, `science`, `land`, `argentina`, `opportunities`, `contribute`, `approach`, `discuss`) and the closing is `<footer id="closing">`.
- Images and videos: put the file in `media/` and point the `src="media/..."` attribute at it.
- Portfolio link: search `index.html` for `dolores-rivera.vercel.app`.

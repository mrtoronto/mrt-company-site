# mrt — Brand Assets

A small umbrella site for a few weird, wonderful little software projects.
This file documents the image-generation prompts used for the site's
visual identity so they're easy to iterate on later.

## Favicon — "Soft Drippy Blob" (v1)

Direction: an abstract gradient blob mascot with personality. No face,
no literal symbols. Friendly, slightly weird, sticker-like.

### Prompt

A small, friendly abstract blob mascot rendered as a single icon on a
clean removable background. The blob is a rounded, slightly asymmetric
shape — somewhere between a melting marshmallow, a pebble, and a sleepy
ghost — with a soft squishy silhouette and one or two gentle drips along
the bottom edge. It feels alive without having a face: maybe a single
tiny highlight that reads almost like a half-closed eye, or no features
at all, just confident presence and good posture.

The surface is a smooth, glossy gradient blending coral-orange into hot
pink into violet into cyan, distributed across the form like a soft
sunset wrapped around a stone. Subtle inner glow, gentle specular
highlight on the upper left, a small soft shadow underneath grounding
it. Light grain texture for a printed-sticker feel. A thin soft outline
in deep aubergine, not a thick black cartoon stroke.

Square composition, centered, generous negative space, neutral
background that can be cleanly removed. No face, no eyes, no text, no
letters, no logos, no sparkles, no AI-glow, no thick black outlines,
no chibi mascot styling.

### Notes

- Generated background is near-white; remove background before exporting
  favicon variants (16, 32, 180, 192, 512, plus SVG if possible).
- Keep the deep-aubergine outline visible on light browser tab themes.

## OpenGraph Image — "Gallery Poster" (v1)

Direction: make `MRT` the hero. The blob/gradient language should support
the typography as abstract marks, not act as a mascot. Artsy, restrained,
less cartoon, no space/nebula background.

### Prompt

Create a 1200x630 OpenGraph image for MRT, a personal umbrella site for
experimental software projects. Make it feel like a contemporary gallery
poster, not a startup banner. Do not include quotation marks. The only
readable text should be MRT.

Place large custom lettering reading MRT slightly left of center. MR should
be dark aubergine, and T should be a saturated gradient of coral, magenta,
violet, and cyan. Around the letters, add a few abstract gradient forms:
soft irregular blobs, smears, and drips, like poured ink or translucent
resin stains on paper. These forms should support the typography, not
become cute characters. Use lots of negative space.

Background: warm cream or pale gray paper, visible grain, faint scanner
texture, subtle print imperfections. Style: editorial design, art book
cover, risograph-inspired but polished, weird and tasteful. No mascot,
no faces, no space, no nebula, no sparkles, no subtext, no UI elements,
no childish cartoon styling.

### Notes

- Site metadata points to `https://mrt-company.com/assets/og-image.jpg`.
- Source generation file in the repo is `assets/og_image.jpg`.
- Optimized deployed file is `assets/og-image.jpg` at 1200x630.
- If regenerating, keep the final asset at 1200x630 and preserve the
  `og-image.jpg` filename unless the metadata in `index.html` changes too.
- iMessage and other scrapers may cache previews by URL. Test updates with
  a cache-busted URL such as `https://mrt-company.com/?v=2`.

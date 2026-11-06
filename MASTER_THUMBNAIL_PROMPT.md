# Master Thumbnail Prompt — Megaproject Construction Niche

One reusable prompt that produces 5 click-worthy thumbnail concepts and ready-to-paste image prompts for any megaproject video. The channel's thumbnail style is built in, so no reference thumbnails are needed.

**How to use:** copy everything inside the box into a new Claude chat, fill in the `INPUTS` lines, and send. Paste the image prompts it gives you into your image generator (Midjourney, Ideogram, Flux, DALL·E, Leonardo, etc.).

```
You are a YouTube thumbnail designer for a megaproject construction documentary channel (bridges, tunnels, dams, airports, artificial islands, megastructures). Your thumbnails get clicks by making a real engineering project look impossible, dangerous or awe-inspiring at a glance. All concepts must be original.

INPUTS
- Topic: [NAME OF THE MEGAPROJECT, e.g. "Gotthard Base Tunnel, Switzerland"]
- Video title (optional): [PASTE THE TITLE, OR WRITE "none"]
- Key hook or number (optional): [e.g. "2,300 m of rock overhead", "sinks 10 cm a year", OR WRITE "none"]
- Image generator (optional): [e.g. Midjourney, Ideogram, Flux, DALL·E, OR WRITE "any"]

STEP 1 — FIND THE HOOKS (do this silently, do not print)
List the project's most extreme, visual facts: size, depth, height, danger, a disaster, an impossible location, a near-failure, a world record. Pick the 5 strongest and give each thumbnail a different one.

STEP 2 — THUMBNAIL STYLE (every thumbnail must follow this)
Look
- Hyper-realistic, hyper-saturated, bright and punchy. This is the opposite of the moody in-video look.
- Photoreal rendering with slightly exaggerated colour, contrast and scale.

Composition
- ONE impossible hero structure fills 60–80% of the frame. Show it at its most extreme: exaggerated scale, a sharp tilt, a dramatic curve, a sheer drop, crashing water, a cut-away cross-section, or a machine bursting through rock.
- Use a strong diagonal, usually from a bottom corner up into the distance, to create depth.
- Add tiny everyday scale cues: cars, a bright orange truck, a red car, small workers in orange hi-vis, a train, a diver.
- Keep it simple: one idea, no clutter, readable at phone size.
- Keep the bottom-right corner clear (the YouTube timestamp covers it).

Colour
- One dominant natural colour field: turquoise sea, lush green cliffs, deep underwater blue, snowy peaks under a bright blue sky.
- The hero structure in bright white, pale concrete, steel or warm interior light so it pops off the background.
- One or two small, saturated warm accents as focal points: orange truck, red car, red arrow, warm window lights, orange hi-vis.
- Light rays, sunbursts or glowing highlights for awe.

Text (optional)
- At least 2 of the 5 thumbnails must have NO text.
- When used: 1–3 words max, heavy condensed all-caps sans-serif, one word bright yellow and one white, thick dark outline, on a tilted black slab in the TOP-LEFT corner only. Never cover the hero subject.
- Text must add something the image cannot show (a number, a threat, a twist). It must not repeat the title.

Graphic extras (optional)
- A big bold curved red arrow pointing at the key detail. Use it on at most 2 thumbnails.

Emotion triggers (each thumbnail must hit at least one, and the 5 together should cover at least 4)
- "That can't be real": impossible geometry or placement
- Danger and tension: about to collapse, flood, sink, crash
- Awe at scale: tiny people and vehicles against something enormous
- Curiosity: a hidden or cut-away view that begs "how?"
- Contrast: calm everyday life in a terrifying setting

Never
- No logos, brand names, real people's faces, watermarks or channel names.
- No cluttered collages or split screens.
- No dark, desaturated or moody grading.
- No copying of existing thumbnails. Match the style, not the image.

STEP 3 — OUTPUT
Generate 5 thumbnails. For each, print exactly:

THUMBNAIL N — [short name]
- Hook used: [the fact it sells]
- Visual concept: 1–2 sentences describing the scene
- Text overlay: [the words and colours, or "None"]
- Arrow: [what it points at, or "None"]
- Emotion trigger: [which one(s) and why it makes people click]
- Image prompt: one fully standalone paragraph for the image generator. Include: the hero structure and what makes it extreme, the setting, the scale cues, the dominant colour field and accents, lighting and light rays, camera angle and lens feel, composition (diagonal, 60–80% fill, empty top-left if text is used, clear bottom-right), "hyper-realistic, hyper-saturated YouTube thumbnail, 16:9, crisp detail". If an image generator was named, adapt the format to it (e.g. add "--ar 16:9 --style raw" for Midjourney; put the overlay text in quotes for Ideogram).
- Negative prompt: blurry, low detail, desaturated, dark, moody, cluttered, text errors, watermark, logo, distorted vehicles, extra limbs

After the 5 thumbnails, print:
- "Top pick: Thumbnail N" with one sentence on why it will get the highest click-through.
- "A/B test pair: Thumbnail N vs Thumbnail M" (two concepts different enough to be a fair test).
```

## Tips

- If your image generator struggles with text, generate the image with no text and add the yellow and white words on a tilted black slab yourself in Canva or Photoshop.
- Check every thumbnail at phone size before uploading. If the idea isn't clear in one second, simplify it.
- Rotate the A/B test pair with YouTube's "Test & Compare" feature to see which style your audience clicks most.

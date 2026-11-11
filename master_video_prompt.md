# Master Video Prompt: Company History Channel

There are two parts:
- **Part A:** paste into Claude together with your image prompts (from the master image prompt). It writes a video prompt for every beat.
- **Part B:** a fill-in template you can paste straight into any image-to-video tool for a single clip.

---

## Part A: Image Prompts → All Video Prompts (paste into Claude)

```
You are the animation director for a faceless YouTube channel that tells the entire history of famous companies in a flat 2D hand-drawn stick-figure cartoon style. Turn every image prompt below into a matching video prompt for an image-to-video AI tool.

COMPANY: [COMPANY / BRAND]
IMAGE PROMPTS:
[PASTE ALL BEATS HERE — each with Beat #, Script, Image prompt, Camera angle, Lighting, Mood, Action]

FOR EVERY BEAT, OUTPUT:
Beat [#] · [duration]s
Script: "[exact script text]"
Video prompt: [one fully standalone paragraph, see rules]

DURATION
- Duration = script words ÷ 2.6, rounded, clamped to 3–5 seconds.

VIDEO PROMPT RULES
- Fully standalone: restate the full scene (characters with their fixed descriptions, setting, key props). Never say "same as before".
- Assume the image is the FIRST FRAME. Describe only what MOVES; never ask the tool to change the composition, characters, or on-image text.
- Structure every prompt in this order:
  1. "[X]-second 2D cartoon animation."
  2. Scene: one-sentence restatement of the image.
  3. Main motion: ONE clear action that matches the script line (taken from the Action field), animated with snappy squash-and-stretch timing.
  4. Face: one expression change that sells the emotion (blink, eyebrow raise, jaw drop, smirk, wink, sweat drop, eyes widen).
  5. Camera movement: ONE move only, picked from the camera angle:
     • wide shot → slow cinematic push-in toward the focal subject
     • medium shot → gentle drift with a slight push-in
     • close-up → subtle slow push-in
     • extreme close-up → very slow macro push-in
     • low angle → slow upward tilt with a gentle push-in, emphasizing scale
     • top-down / map → slow overhead drift with a gentle push-in
     • side tracking → smooth lateral tracking move following the subject
     • split panels / grid → static frame; panels pop in one after another with a quick bounce
  6. Background motion: 1–2 small ambient details matched to the lighting:
     • indoor/historic → lamp glow flickers softly, dust motes float
     • outdoor day → clouds drift slowly, background figures move naturally
     • hot country → heat shimmer, leaves and awnings sway gently
     • night/party → neon and lamp lights flicker softly, faint haze drifts
     • reveal/product → light beams shimmer, small sparkles drift
     • sports/arena → crowd bobs and waves, flashbulbs pop
     • office/lab/court → background figures shift and blink, papers rustle
     • sky/space → thin clouds drift far below, faint glints on the subject
  7. Mood: 1–3 words.
  8. Style lock (append unchanged): "Keep the flat hand-drawn stick-figure style with large round white heads, bold black wobbly outlines, muted warm vintage palette with red accents, subtle paper texture, limited 2D cartoon animation with slight line boil, no realistic rendering, no 3D, no morphing, no new characters, no text changes, 16:9, end on a clean held final pose."
- Keep motion simple and readable: one main action + one camera move + small ambient motion. Busy motion breaks the style.
- Comedic beats: add a quick exaggerated reaction (jump, flail, faint, slow clap) on the punchline.
- Number, chart, and map beats: animate the data element itself (arrow drawing, bar rising, icons popping, stamp slamming, counter ticking).

FINAL CHECK (output at the end)
- Total video prompts: X (must equal total image beats)
- Total runtime: X minutes
```

---

## Part B: Single Clip Template (paste straight into an image-to-video tool)

```
[3/4/5]-second 2D cartoon animation. Scene: [one-sentence description of the image — main character with fixed description, setting, key props]. Main motion: [ONE action matching the script line], with snappy squash-and-stretch timing. Face: [one expression change]. Camera movement: [ONE move: slow push-in / upward tilt / overhead drift / lateral tracking / static with panels popping in]. Background motion: [1–2 ambient details]. Mood: [1–3 words].

Keep the flat hand-drawn stick-figure style with large round white heads, bold black wobbly outlines, muted warm vintage palette with red accents, subtle paper texture, limited 2D cartoon animation with slight line boil, no realistic rendering, no 3D, no morphing, no new characters, no text changes, 16:9, end on a clean held final pose.
```

**Example:**
> 4-second 2D cartoon animation. Scene: a stick-figure pharmacist with a large round white head, round glasses and a handlebar mustache, in a white apron, standing beside an empty cash drawer in a cluttered 1880s drugstore, a chalkboard reading 'SALES 1886' with a red arrow crashing down. Main motion: the red chalk arrow draws itself downward as he grabs his head in panic, with snappy squash-and-stretch timing. Face: jaw drops and sweat drops fly off his head. Camera movement: gentle drift with a slight push-in. Background motion: oil lamp glow flickers softly, dust motes float. Mood: panic, comedic. *[style lock]*

---

## Tips
- Generate the image first, then use it as the first frame. Image-to-video keeps the style far more consistent than text-to-video.
- If a clip warps faces or adds realism, rerun it with "minimal motion, keep the character exactly as in the image" added.
- For long scripts, Claude may stop partway. Reply "continue from Beat [#]" to get the rest.
- Full workflow: master script prompt → master image prompt → this prompt.

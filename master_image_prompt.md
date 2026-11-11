# Master Image Prompt: Company History Channel

There are three parts:
- **Part A:** paste into Claude together with your finished script. It writes every image prompt for the video.
- **Part B:** a fill-in template you can paste straight into any image generator for a single scene.
- **Part C:** a fill-in template for thumbnails.

---

## Part A: Script → All Image Prompts (paste into Claude)

```
You are the visual director for a faceless YouTube channel that tells the entire history of famous companies. Turn the script below into image prompts for every beat.

COMPANY: [COMPANY / BRAND]
SCRIPT:
[PASTE FULL SCRIPT HERE]

STEP 1: CHARACTER SHEET (output this first)
List every recurring character (founders, CEOs, key people, plus "the narrator mascot") with a fixed visual description you will reuse WORD FOR WORD in every prompt they appear in:
- All characters are stick figures with large round white heads, black dot eyes, thin black stick limbs.
- Give each one 2–4 identifying features only: hair (style + color), facial hair, glasses, and one signature outfit (e.g. "white suit and string tie", "navy blazer over open white shirt").
- Add age variants if the story spans decades (young / middle-aged / elderly).
- The narrator mascot: a stick figure with a large round white head, one raised eyebrow and a smirk, charcoal suit, white shirt, red tie. Use him for asides, jokes, the subscribe line, and the outro.
- Also define 1–3 recurring PRODUCT descriptions (e.g. the original bottle, the modern can) to reuse word for word.

STEP 2: SPLIT THE SCRIPT INTO BEATS
- Each beat = max 13 words of script (3–5 seconds at ~2.6 words/second). Split at natural phrase breaks.
- Cover the ENTIRE script in order. Do not skip, merge away, or paraphrase any words.

STEP 3: FOR EVERY BEAT, OUTPUT:
Beat [#]
Script: "[exact script text for this beat]"
Image prompt: [one fully standalone paragraph, see rules]
Camera angle: [...]
Lighting: [...]
Mood: [...]
Action: [...]

IMAGE PROMPT RULES
- Fully standalone: never say "same as before" or "the previous scene". Repeat the full character and product descriptions every time.
- Include: subject + what they are doing, environment with 3–5 era-specific props, camera angle, lighting, mood, and the style block below.
- Show the beat LITERALLY and VISUALLY. Turn abstract ideas into objects:
  • money/prices → cash stacks, checks, price tags, money bags with hand-lettered amounts
  • growth/decline → chalkboard or whiteboard charts with a big arrow
  • dates → wall calendar, sign, or plaque with the year hand-lettered
  • expansion → cartoon map with icons popping up across countries
  • failure/rejection → big red X or red "DENIED"/"FAIL" stamp
  • ideas → lightbulb or thought bubble
  • ownership splits → pie charts
  • comparisons → side-by-side split panels
  • lists of 3+ items → multi-panel grid, one item per panel
- Jokes and narrator asides → the narrator mascot reacting (smirk, shrug, wink, facepalm, slow clap).
- On-image text: max 1–5 words, hand-lettered (years, prices, short labels). Never full sentences.
- One clear focal subject per image. Exaggerated facial emotion that matches the line.
- Vary the camera across beats: wide establishing, medium, close-up, top-down map, low angle for power, split panels for comparisons.
- Era accuracy: clothes, vehicles, tech, and buildings must match the year in the script.
- Real brand logos: describe them generically (e.g. "a slim silver-and-blue can with two charging red bulls") rather than naming trademarks.

STYLE BLOCK (append to the end of EVERY image prompt, unchanged):
Flat 2D hand-drawn cartoon illustration, stick-figure characters with large round white heads, black dot eyes, thin black stick limbs and highly expressive faces, bold even black outlines with slight hand-drawn wobble, muted warm vintage palette (tan, sepia, olive green, mustard, terracotta, dusty teal) with bold red accents, flat even lighting, minimal soft shading, subtle paper texture, detailed storybook background props, humorous editorial explainer style, 16:9 landscape

LIGHTING PRESETS (pick one per beat)
- Indoor/historic: warm amber glow from hanging bulbs and oil lamps
- Outdoor day: bright flat daylight with simple soft shadows
- Hot country: hot bright sunlight, warm yellow cast
- Night/party/club: cool dusty-teal night tones with warm yellow accent lights
- Reveal/product: soft cream spotlight cones from above
- Sports/arena: bright stadium floodlights drawn as simple flat beams
- Office/lab/court: flat cool office light with warm desk-lamp accents
- Sky/space: flat deep navy sky fading to pale blue, soft rim glow

FINAL CHECK (output at the end)
- Total beats: X
- Confirm: every word of the script is covered in order (yes/no)
- Estimated runtime: X minutes
```

---

## Part B: Single Scene Template (paste straight into an image generator)

```
[SUBJECT: who, with fixed description — e.g. "an Austrian stick-figure man with a large round white head, messy wavy brown hair, light stubble, open-collar white shirt under a navy blazer"] [ACTION: what they're doing, with a clear facial expression] in [SETTING: place + era, with 3–5 specific props]. [Optional on-image text: 'SHORT LABEL' hand-lettered on a sign/calendar/chalkboard]. Camera: [wide / medium / close-up / top-down / low angle / split panels]. Lighting: [pick a preset]. Mood: [1–3 words].

Flat 2D hand-drawn cartoon illustration, stick-figure characters with large round white heads, black dot eyes, thin black stick limbs and highly expressive faces, bold even black outlines with slight hand-drawn wobble, muted warm vintage palette (tan, sepia, olive green, mustard, terracotta, dusty teal) with bold red accents, flat even lighting, minimal soft shading, subtle paper texture, detailed storybook background props, humorous editorial explainer style, 16:9 landscape
```

**Example:**
> A stick-figure pharmacist with a large round white head, round glasses and a handlebar mustache, wearing a white apron, clutching his head in panic beside an empty cash drawer in a cluttered 1880s drugstore with wooden shelves of jars, barrels and an oil lamp. A chalkboard reads 'SALES 1886' with a red arrow crashing down. Camera: medium shot, eye level. Lighting: warm amber glow from oil lamps. Mood: panic, comedic. *[style block]*

---

## Part C: Thumbnail Template

```
YouTube thumbnail. On the left third: a semi-realistic cartoon caricature of [FOUNDER/CEO: age, hair, face, signature outfit], arms crossed, confident slight smirk, looking straight at the viewer, waist-up, with a thin white sticker outline and red-orange outer edge. Background: high-angle bird's-eye cartoon view of [ICONIC PLACE: HQ / campus / factory / origin town] with tiny people, vehicles and roads, under a light airy blue sky with soft white clouds. Top right: huge heavy black all-caps serif text "[BRAND]" with "[FOUNDING YEAR] – [CURRENT YEAR]" below it, and a rounded-square app-style icon of [BRAND SYMBOL] beside the title. Floating sticker-style objects down the right edge: [3–5 items: origin object, signature products, a milestone object, a rising green arrow].

Style: bright, detailed hand-drawn cartoon, thick clean black outlines, bright clean saturated poster colors, crisp, readable at small size, 16:9, 1280x720
```

**Title formula:** The ENTIRE History of [BRAND] in [N] Minutes

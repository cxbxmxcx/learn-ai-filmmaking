# Day 2: Light, Lens and Look

*A man throwing the most careful candlelit dinner of his life flips on the string lights and reveals that the guest of honor is his golden retriever, and this is her adoption day.*

Watch: https://cxbxmxcx.github.io/learn-ai-filmmaking/day-2-light-lens-and-look/

## The generation prompt

Model endpoint on fal: `bytedance/seedance-2.5/text-to-video`. Seed returned: `61022693`.

```
Settings
Model: Seedance 2.5, text-to-video, no reference images
Duration: 15 seconds
Aspect ratio: 16:9
Resolution: 720p
Audio: on
Seed: any (write it down if you like the result)

Prompt
A man in a rolled-sleeve shirt sets a candlelit dinner table with painstaking care in a dim dining room, lit only by one candle, and when he reaches up and switches on a string of warm bulbs above the table, the light spreads across the room and reveals a golden retriever in a black bow tie sitting upright at the head of the table.

Look: 40mm, shallow depth of field, 24 fps, fine 35mm film grain, slight halation around the candle and the bulbs, warm and softly contrasted, natural skin tones, a lived-in family dining room, not a commercial.

[0 to 6 seconds] Locked-off medium shot from the side of the table, eye level. Low-key lighting: a single candle flame is the only source, a warm 1850K glow on his hands and face, soft shadows falling off fast into darkness. He straightens a fork, pours water into a glass, and adjusts a folded napkin. The far end of the table is in complete darkness.
[6 to 9 seconds] He reaches up and pulls the cord of the string lights hanging above the table. The bulbs flicker once and come on at a warm 2700K, and the light spreads across the whole room: cream walls, framed photos, and an unlit bone-shaped cake on a plate at the far end of the table.
[9 to 15 seconds] High-key warm light on everything. At the head of the table a golden retriever in a black bow tie sits upright on a dining chair, ears up, tail wagging against the chair back. The man sits down opposite, raises his water glass to the dog, and the dog tilts its head. A slow, gentle push-in toward the two of them.

Audio: the faint hiss of a candle flame, cutlery and glass being set down, the click of the light switch, the soft buzz of the bulbs coming on, a tail thumping against wood, one soft huff from the dog. No music, no dialogue.

Constraints: one continuous shot with no cuts, one man and one dog only, no other people, no readable text, the dog must not be visible before the lights come on, the far end of the table stays dark for the first six seconds, no flicker after the lights are on, no identity change, no extra limbs.
```

## Infographic prompts (Nano Banana Pro, 16:9, 2K)

### Figure 2.1: Light is a state. The same room, the same table, two different stories.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "LIGHT IS A STATE" with a lighter mixed-case subtitle "The same room, two different stories". Layout: two large rounded frames side by side, each a simple line illustration of the same dining table from the side. Left frame, lavender border, label above "STATE A: LOW KEY": one candle on the table, a man adjusting a fork, the far end of the table shaded dark, caption below "AUDIENCE READS: a romantic dinner". Right frame, peach border, label above "STATE B: HIGH KEY": string lights lit above the table, the whole room visible, a golden retriever in a bow tie seated at the far end, caption below "AUDIENCE READS: the guest of honor". Between the frames a teal arrow pointing right with the label "CAUSE: he pulls the cord". Under both frames, three small cards in a row: light blue "SOURCE: one candle, then string lights", mint "QUALITY: soft, then softer and everywhere", rose "COLOR: 1850K candle, then 2700K bulbs". Full-width teal banner across the bottom reading "KEY INSIGHT: A change of light is a change of state. Give it a cause and the viewer believes it." in white. Legible sans-serif type, thin matching borders, simple black line drawings, no gradients, no 3D, no photographic textures.
```

Correction appended for the published take:

```
The title must read exactly LIGHT IS A STATE and nothing else: do not write the words EDUCATIONAL INFOGRAPHIC, or any other style or instruction words, anywhere on the image.
```

### Figure 2.2: The three questions of light, with the kelvin scale every prompt should use.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE THREE QUESTIONS OF LIGHT" with a lighter mixed-case subtitle "Answer these and you have described the light". Layout: top half, three rounded cards in a row. Light blue "WHERE FROM?" with body "Source. A window, a lamp, a candle, a screen. If the viewer can see the reason, the light is motivated." and a black line icon of a window. Mint "HOW HARD?" with body "Quality. Small or far sources are hard and sharp; large or diffused sources are soft and kind." and an icon of a sun beside a cloud. Peach "WHAT COLOR?" with body "Temperature in kelvin. Warm is low, cool is high. Name the number." and an icon of a thermometer. Bottom half: a wide horizontal bar shaded smoothly from deep orange on the left to pale blue on the right, with tick marks and labels above it: "1850K candle", "2700K household bulb and string lights", "3200K tungsten film light", "5600K midday sun", "6500K overcast sky", "8000K open shade and blue hour". Beneath the bar, a small light grey card reads "The model reads kelvin numbers more reliably than adjectives like warm or cool". Full-width teal banner across the bottom reading "KEY INSIGHT: Source, quality, color. Name all three, and name the number." in white. Legible sans-serif type, thin matching borders, simple black line icons, no 3D, no photographic textures.
```

### Figure 2.3: The lighting vocabulary, twelve named styles and the mood each one carries.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE LIGHTING VOCABULARY" with a lighter mixed-case subtitle "Twelve styles a model already understands". Layout: a grid of twelve rounded pastel cards, four columns by three rows, each with a small black line icon of a face lit from a different direction, an all-caps label and a short mood line. Row 1: light blue "HIGH KEY" "Bright, even, few shadows. Comedy, warmth, openness."; light blue "LOW KEY" "One source, deep shadows. Mystery, tension, romance."; mint "NATURAL" "Sun or sky, no additions. Documentary honesty."; mint "MOTIVATED" "Light from a source in the scene. Realism." Row 2: peach "PRACTICAL" "Visible lamps, candles, neon. Atmosphere."; peach "REMBRANDT" "Key at 45 degrees, a triangle of light on the far cheek. Classic portraits."; lavender "CHIAROSCURO" "Extreme contrast of light and dark. Drama, moral ambiguity."; lavender "SILHOUETTE" "Backlit shape against brightness. Mystery, anonymity." Row 3: rose "HARD" "Sharp shadows, texture. Tension, heat."; rose "SOFT" "Gentle shadows, flattering. Intimacy, memory."; light teal "UNDER" "Light from below. Unease, horror, campfire stories."; light teal "TOP" "Light from above. Isolation, interrogation." Full-width teal banner across the bottom reading "KEY INSIGHT: Pick two or three styles for a film and stay inside them. Consistency is the look." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 2.4: The camera package, and the single line it turns into at the top of every prompt.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE CAMERA PACKAGE" with a lighter mixed-case subtitle "Words that change the image, whether or not you own the gear". Layout: five rounded cards in a row across the top with black line icons. Light blue "FOCAL LENGTH" icon of a lens, body "24mm stretches, 35 to 40mm feels human, 85mm isolates a face". Mint "DEPTH OF FIELD" icon of a sharp circle beside a blurred circle, body "Shallow reads as cinema, deep reads as documentary". Peach "FRAME RATE" icon of a film strip, body "24 fps looks like film, 60 fps looks like a phone". Lavender "SHUTTER AND MOTION BLUR" icon of a blurred arrow, body "Normal shutter blurs motion the way eyes expect". Rose "STOCK AND GRAIN" icon of speckled dots, body "Fine grain, slight halation, honest color". Beneath the row, a wide light grey card with a single line of navy text in a monospace style: "Look: 40mm, shallow depth of field, 24 fps, fine 35mm film grain, slight halation, natural skin tones". Under that card a teal arrow pointing down to a small light teal card reading "PASTE THIS LINE AT THE TOP OF EVERY PROMPT IN THE FILM". Full-width teal banner across the bottom reading "KEY INSIGHT: The package is one sentence. Write it once and never change it inside a film." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 2.5: Color grammar, three dials the audience already knows how to read.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "COLOR GRAMMAR" with a lighter mixed-case subtitle "Three dials the audience reads without noticing". Layout: three tall rounded cards side by side, each with a horizontal slider drawn as a thin bar with a dot. Peach "TEMPERATURE", slider labelled "WARM" at left and "COOL" at right, body "Warm: home, comfort, nostalgia. Cool: night, distance, technology, calm." Mint "SATURATION", slider labelled "MUTED" at left and "RICH" at right, body "Muted reads as real and documentary. Rich reads as heightened, dream, musical." Lavender "CONTRAST", slider labelled "SOFT" at left and "HARD" at right, body "Soft reads gentle and intimate. Hard reads dramatic and tense." Beneath the three cards, a wide rose card reads "CAUTION: teal shadows with orange skin is the most common grade in the world. Use it on purpose or not at all." Beneath that, a small light grey card reads "One look per film. Change the light inside a scene, not the grade." Full-width teal banner across the bottom reading "KEY INSIGHT: Set the three dials once for the film, then tell the story with light." in white. Legible sans-serif type, thin matching borders, simple black line icons, no gradients, no 3D, no photographic textures.
```

### Figure 2.6: The look header. Camera package, grade and lighting in one block, reused across a film.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE LOOK HEADER" with a lighter mixed-case subtitle "One block of words that keeps a whole film consistent". Layout: a tall light grey card in the center styled like a document with three stacked pastel bands inside it, each labelled at the left. Band 1, light blue, label "CAMERA": text "40mm, shallow depth of field, 24 fps". Band 2, peach, label "STOCK AND GRADE": text "fine 35mm film grain, slight halation, warm, softly contrasted, natural skin tones". Band 3, lavender, label "LIGHTING": text "State A: one candle, 1850K, low key. Cause: he pulls the cord. State B: string lights, 2700K, high key". To the left of the document, a mint card with an arrow pointing into it reads "WRITTEN ONCE PER FILM". To the right, a rose card with an arrow pointing out reads "CHANGES ONLY THE LIGHTING LINE PER SCENE". Beneath the document, three small light teal cards in a row reading "SUBJECT AND ACTION FIRST", "THEN THE LOOK HEADER", "THEN THE TIME WINDOWS". Full-width teal banner across the bottom reading "KEY INSIGHT: Describe the light twice and the cause once, and the model will change state on cue." in white. Legible sans-serif type, thin matching borders, simple black line icons, no gradients, no 3D, no photographic textures.
```

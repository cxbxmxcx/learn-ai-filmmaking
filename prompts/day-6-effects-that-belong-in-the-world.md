# Day 6: Effects That Belong in the World

*At the school science fair, a nervous kid's papier-mache volcano erupts far bigger than planned, and the drenched judge gives it two thumbs up.*

Watch: https://cxbxmxcx.github.io/learn-ai-filmmaking/day-6-effects-that-belong-in-the-world/

## The generation prompt

Model endpoint on fal: `bytedance/seedance-2.5/text-to-video`. Seed returned: `56165276`.

```
Settings
Model: Seedance 2.5, text-to-video, no reference images
Duration: 30 seconds
Aspect ratio: 16:9
Resolution: 720p
Audio: on
Seed: any (write it down if you like the result)

Prompt
At a school science fair in a gymnasium, a nervous twelve-year-old boy in oversized safety goggles pours vinegar into a lumpy papier-mache volcano and it erupts far bigger than anyone expected, blasting a column of pink foam over the table and drenching the judge, who wipes one lens of her glasses and slowly raises both thumbs.

Look: 35mm, 24 fps, fine 35mm film grain, flat school-gym fluorescent light with a wet pink bounce off the foam on nearby faces, handheld documentary feel, saturated but realistic colors, a real school gym, not a commercial.

[0 to 6 seconds] Medium shot, eye level. A gym lined with folding tables and tri-fold poster boards, a basketball hoop high in the background. The boy tips a plastic jug and pours vinegar into the crater of the brown papier-mache volcano on his table. A judge in a blazer with a clipboard leans in close, unimpressed. Other kids crowd behind the table.
[6 to 10 seconds] A low gurgle. The volcano trembles, a first pink bubble swells at the crater, and the kids around the table take one step back. The judge does not move.
[10 to 17 seconds] Slow motion. The crater blows: a thick column of pink foam blasts upward, catching the fluorescent light with a wet glisten, breaking into blobs and droplets of every size, arcing outward and falling under gravity, the heaviest blobs first, a rolling wave of foam pouring over the table edge and across the floor. Foam flies past the camera in the foreground and briefly blocks the judge. The clipboard flies out of her hand. The camera lurches with the blast and steadies over a second.
[17 to 24 seconds] Normal speed. The judge stands drenched head to toe in pink foam, her glasses coated, foam sliding off her shoulders in slow drips. A faint pink mist hangs in the air. Foam hangs from the basketball hoop above and patters onto the floor. Everyone is silent. She lifts one finger and wipes a single lens of her glasses clean.
[24 to 30 seconds] She looks at the boy for a long beat, then slowly raises both thumbs. The gym erupts in cheering, the boy's face splits into a grin, and pink foam keeps dripping from the hoop.

Audio: gym echo and kids murmuring, the glug of vinegar pouring, a low rising gurgle, then a sharp wet blast with a deep body and a long gym-reverb tail, foam splattering on the table and floor, droplets pattering from the hoop, dead silence, one squeak of a finger on a wet lens, then a wall of cheering. No music, no dialogue.

Constraints: cuts only where the time windows change, one boy and one judge in focus with other kids in the background only, no readable text on the poster boards or the clipboard, no foam before ten seconds, physically plausible arcs and drips, the foam must light nearby faces and stay on every surface it lands on, no identity drift, no extra limbs.
```

## Infographic prompts (Nano Banana Pro, 16:9, 2K)

### Figure 6.1: The ten pillars of a believable effect. Everything a real event does to the world around it.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE TEN PILLARS OF A BELIEVABLE EFFECT" with a lighter mixed-case subtitle "Everything a real event does to the world around it". Layout: a grid of ten rounded pastel cards in two rows of five, each with a number, a black line icon, an all-caps label and one short line. Row 1: light blue "1 CAUSE, PEAK, AFTERMATH" icon of a three-step timeline, "Something triggers it, it peaks, it leaves consequences"; light blue "2 LIGHT" icon of a glowing bulb, "The effect illuminates its surroundings"; mint "3 SHADOW AND OCCLUSION" icon of a cloud in front of a figure, "It casts shadows and passes in front of things"; mint "4 SCALE" icon of a tall and a small figure, "Reference objects say how big it is"; peach "5 PHYSICS" icon of a parabolic arc, "Gravity, inertia, drag". Row 2: peach "6 PARTICLES" icon of scattered dots of three sizes, "Debris at many sizes, each with a lifetime"; lavender "7 ATMOSPHERE" icon of light rays through haze, "Mist, smoke and steam make space visible"; lavender "8 CAMERA RESPONSE" icon of a shaking camera, "The camera flinches, refocuses, blurs"; rose "9 RESIDUE" icon of a puddle, "The world stays marked afterwards"; rose "10 SOUND" icon of a waveform, "Transient, body, tail, in the right room". Beneath the grid, a small light grey card reads "Not every effect needs all ten at full strength. Every effect needs the ones its audience would notice missing." Full-width teal banner across the bottom reading "KEY INSIGHT: An effect is believable when the world reacts to it. Prompt the reaction, not just the event." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 6.2: Cause, peak, aftermath. The three-act structure of an effect, timed for our volcano.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "CAUSE, PEAK, AFTERMATH" with a lighter mixed-case subtitle "An effect is a three-act story in a few seconds". Layout: a horizontal timeline bar across the middle from 0 to 30 seconds divided into five colored segments with labels above: light blue "0 to 6 s CAUSE: the vinegar pours", mint "6 to 10 s ANTICIPATION: the gurgle, the kids step back", peach "10 to 17 s PEAK: the eruption, slow motion", lavender "17 to 24 s AFTERMATH: foam on everything, silence", rose "24 to 30 s REACTION: two thumbs up, the gym erupts". Above the bar, a simple black line curve rises slowly through the first two segments, spikes sharply in the peach segment, and decays slowly through the last two, labelled "ENERGY". Beneath the bar, three small cards: light blue "VISIBLE TRIGGER: the audience must see the cause", peach "BRIEF OVEREXPOSURE AT THE PEAK: real cameras clip", rose "RESIDUE PERSISTS: what changed stays changed". Full-width teal banner across the bottom reading "KEY INSIGHT: Give the cause more screen time than you think it deserves. Dread is the effect's setup." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

Correction appended for the published take:

```
Spell every label exactly once with no repeated words: the third segment label reads exactly: 10 to 17 s PEAK: the eruption, slow motion (the word 'the' appears only once in it).
```

### Figure 6.3: Effects light the world and leave marks. Color temperature and residue by effect type.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "EFFECTS LIGHT THE WORLD AND LEAVE MARKS" with a lighter mixed-case subtitle "Pillars 2 and 9, the two most often forgotten". Layout: a table drawn as five rounded rows, each row split into three cells: an effect, its light, its residue. Row 1, peach: "FIRE" "warm orange, about 1800K, flickering on every nearby surface" "scorch marks, smoke, embers that fade". Row 2, light blue: "LIGHTNING" "cold blue-white, 6500K and above, one frame of overexposure" "a residual glow on metal, splintered wood". Row 3, lavender: "NEON OR MAGIC" "unnatural magenta or cyan cast on faces" "a lingering glow, dust in the air". Row 4, mint: "WATER OR FOAM" "wet glisten, bounce of whatever lights the room" "wet surfaces, drips, puddles that stay". Row 5, rose: "OUR VOLCANO" "pink foam under flat gym fluorescents, pink bounce on faces" "foam on the judge, the hoop, the floor, still dripping at the end". A small navy note beneath the table: "Prompt the light on the surroundings, not just on the effect." Full-width teal banner across the bottom reading "KEY INSIGHT: If the walls do not light up and the floor does not stay wet, the audience will not believe it happened." in white. Legible sans-serif type, thin matching borders, simple black line icons, no gradients, no 3D, no photographic textures.
```

### Figure 6.4: Scale, occlusion, physics and particles. The four pillars that put an effect in three dimensions.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "PUTTING THE EFFECT IN THE ROOM" with a lighter mixed-case subtitle "Four pillars that make it three-dimensional". Layout: four rounded pastel cards in a two-by-two grid, each with a simple black line diagram and two lines of text, the second in a monospace style as a prompt phrase. Top left, mint "SCALE": diagram of a foam column beside a small figure and a basketball hoop, "The audience measures with things they know", phrase "a rolling wave of foam pouring over the table edge, foam hanging from the basketball hoop". Top right, light blue "OCCLUSION": diagram of blobs passing in front of a figure, "The effect passes in front of and behind things", phrase "foam flies past the camera in the foreground and briefly blocks the judge". Bottom left, peach "PHYSICS": diagram of three parabolic arcs of different heights, "Gravity, inertia and drag decide every path", phrase "droplets arc outward and fall under gravity, the heaviest first". Bottom right, lavender "PARTICLES": diagram of dots in three sizes with short fading trails, "Debris at many sizes, each with a lifetime", phrase "foam breaking into blobs and droplets of every size, a fine mist hanging last". Full-width teal banner across the bottom reading "KEY INSIGHT: Name the ruler, name the overlap, name the arc, name the sizes. Four phrases turn a layer into an event." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 6.5: The camera is a witness. How a real camera and a real room react to an event.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE CAMERA IS A WITNESS" with a lighter mixed-case subtitle "Pillars 8 and 10: the reactions that prove someone was there". Layout: left half, a light blue card titled "CAMERA RESPONSE" with five small rows, each a black line icon and a phrase in a monospace style: shaking camera "lurches with the blast and steadies over a second", two focus circles "loses focus on the foam and finds the judge again", a smeared arrow "motion blur on the fastest droplets", a sun burst "a bloom of light off the wet foam", a clock "slow motion at the peak, normal speed for the aftermath". Right half, a peach card titled "SOUND STRUCTURE" with a simple black waveform drawn in three labelled parts: a tall spike "TRANSIENT: the sharp wet blast", a wide hump "BODY: the deep whump and splatter", a long decaying tail "TAIL: the gym's echo ringing out". Beneath the waveform, a small card reads "Then the room: dead silence, one squeak of a finger on a wet lens, a wall of cheering." Full-width teal banner across the bottom reading "KEY INSIGHT: Prompt the camera's flinch and the room's echo, and the effect stops being footage of a render." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 6.6: When the prompt gets too big. Prioritize, split, remove contradictions, and let the effect serve the story.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "WHEN THE PROMPT GETS TOO BIG" with a lighter mixed-case subtitle "A decision framework for effects that stop working". Layout: a simple top-down flowchart of rounded cards joined by teal arrows. Top card, light grey: "The result got worse as the prompt got longer". Three arrows to three cards in a row: mint "PRIORITIZE: which three pillars would the audience notice missing? Keep those at full strength, mention the rest once."; peach "SPLIT: give the effect and the reaction their own time windows, or their own shots."; rose "REMOVE CONTRADICTIONS: slow motion versus frantic cuts, dark versus bright, silence versus roar. Pick one." All three arrows lead down to one wide lavender card: "THEN ASK: what is the effect for? Ours is for the judge's face and the kid's grin. If the effect is not serving a person, cut it in half." Beneath, a small navy note: "The reaction shot is where the story lives. The effect is the setup." Full-width teal banner across the bottom reading "KEY INSIGHT: An effect earns its screen time by what it does to a character, not by how big it is." in white. Legible sans-serif type, thin matching borders, simple black line icons, no gradients, no 3D, no photographic textures.
```

Correction appended for the published take:

```
In the bottom THEN ASK card, the left icon is the judge: a woman in a blazer wearing glasses. The right icon is a grinning boy wearing safety goggles. Do not draw an old man.
```

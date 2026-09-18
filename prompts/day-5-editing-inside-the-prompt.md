# Day 5: Editing Inside the Prompt

*A man whose alarm never went off sprints through his morning to reach the office, and finds out the hard way what day it is.*

Watch: https://cxbxmxcx.github.io/learn-ai-filmmaking/day-5-editing-inside-the-prompt/

## The generation prompt

Model endpoint on fal: `bytedance/seedance-2.5/text-to-video`. Seed returned: `300635857`.

```
Settings
Model: Seedance 2.5, text-to-video, no reference images
Duration: 30 seconds
Aspect ratio: 16:9
Resolution: 720p
Audio: on
Seed: any (write it down if you like the result)

Prompt
A man in his thirties with short dark hair and a grey suit wakes to a silent phone, realizes his alarm never fired, and sprints through his morning in shots that get shorter and shorter until he bursts into his office and finds it dark, empty, and being vacuumed by a cleaner who waves at him.

Look: 35mm, 24 fps, fine 35mm film grain, cool grey morning light indoors, muted realistic colors, handheld urgency in the fast shots and a locked-off stillness in the last two, not a commercial.

[0 to 5 seconds] Medium close-up in a bedroom, soft grey morning light. He is asleep face-down, his phone face-up on the nightstand with a dark screen. His eyes open, he grabs the phone, stares at it, and bolts upright with a sharp inhale.
[5 to 9 seconds] Hard cut. Bathroom mirror, medium shot: toothbrush in his mouth, white shirt half-buttoned, one sock on, a tie clamped in his teeth, everything moving fast.
[9 to 12 seconds] Hard cut. Stairwell, wide shot from below: he takes the stairs two at a time, suit jacket in one hand, bag in the other. Under the last second of this shot, the hiss of bus air brakes begins before the cut.
[12 to 14 seconds] Hard cut. Bus doors closing, medium shot from inside the bus: he squeezes sideways through the gap at the last second as the doors thump shut behind him.
[14 to 15.5 seconds] Hard cut. Office lobby, wide shot: he spins through a revolving door and out into the corridor.
[15.5 to 17 seconds] Hard cut. Locked-off close-up of his face, breathless, wide-eyed, mouth slightly open, looking off-screen to the right. He does not move and the camera does not move.
[17 to 22 seconds] Hard cut to what he sees: a wide, locked-off shot of an open-plan office, dark, half the lights off, blinds down, every chair pushed in, no one at any desk. A cleaner in headphones vacuuming between the desks looks up, pulls one earbud out, and gives him a slow, friendly wave.
[22 to 30 seconds] Hard cut back to the identical locked-off close-up of his face with the identical breathless expression, held without change for a long beat. Then he looks down at the phone in his hand, looks back up, exhales all the way, and starts to laugh; he slides down the wall to sit on the floor, still laughing, and raises one hand to wave back. The camera holds.

Audio: near silence and a single bird in the bedroom, then a sharp inhale; running water and a clattering toothbrush cup; footsteps pounding on concrete stairs; the bus air-brake hiss arriving before the bus shot and the doors thumping shut; the revolving door's whoosh; his ragged breathing in the close-up; the flat hum of a vacuum cleaner in the empty office; then his breathing slowing into a laugh under the hum. No music, no dialogue.

Constraints: eight shots joined by hard cuts exactly at the listed times, no dissolves and no fades, the same man with the same face, hair and grey suit in every shot, one cleaner and no other people, no readable text and no visible clocks or phone screens, no camera movement inside the last two shots, the two close-ups are the same framing and the same expression, no identity drift, no extra limbs.
```

## Infographic prompts (Nano Banana Pro, 16:9, 2K)

### Figure 5.1: Coverage and the line. The shots a scene needs, and the rule that keeps them cutting together.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "COVERAGE AND THE LINE" with a lighter mixed-case subtitle "The shots a scene needs, and the rule that keeps them cutting together". Layout: left half, four small rounded cards stacked vertically with black line frame icons: light blue "WIDE" "Where we are", mint "MEDIUM" "Who is doing what", peach "CLOSE-UP" "What they feel", lavender "INSERT" "The detail that matters (the phone, the clock)". Right half, a light grey card containing a simple top-down diagram: two figures facing each other with a dashed navy line drawn through both of them extending across the card, labelled "THE 180-DEGREE LINE", and three camera icons all on the lower side of the line labelled "A", "B", "C" with a teal arc connecting them; a small crossed-out camera icon on the upper side of the line labelled "NEVER CROSS". Beneath the diagram, a caption "Keep every camera on one side of the line and the characters keep looking at each other after the cut." Full-width teal banner across the bottom reading "KEY INSIGHT: Shoot the wide, the medium, the close and the insert, all from one side of the line, and any cut will work." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 5.2: Cut types and their prompt tokens. Six cuts, what each does, and the words that call it.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "CUT TYPES AND THEIR PROMPT TOKENS" with a lighter mixed-case subtitle "Six cuts a model already knows by name". Layout: six rounded pastel cards in two rows of three, each with a small black line diagram of two film frames and an arrow, an all-caps label, one line of effect, and one line in a monospace style showing the token. Row 1: light blue "HARD CUT" "Instant. Time moves forward." token "Hard cut to..."; mint "JUMP CUT" "Same subject, time removed. Jolts." token "Jump cut, same angle, seconds later..."; peach "MATCH CUT" "Two shapes become one idea." token "Match cut from the round clock to the round plate...". Row 2: lavender "SMASH CUT" "Loud to quiet, calm to chaos." token "Smash cut to silence..."; rose "CUTAWAY" "A detail, then back." token "Cut to an insert of the phone, then back to his face..."; light teal "AUDIO BRIDGE" "Sound arrives before or after its picture." token "The hiss of bus brakes begins before the cut...". Beneath the grid, a small light grey card reads "Say 'no dissolves, no fades' in the constraints, or the model softens every cut." Full-width teal banner across the bottom reading "KEY INSIGHT: Put the cut token at the start of the time window. The model reads the first words of a window the way it reads the first words of a prompt." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 5.3: Editing rhythms, and the shape of our film: accelerate, then release.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "EDITING RHYTHMS" with a lighter mixed-case subtitle "Shot length tells the audience how to feel". Layout: top half, four rounded pastel cards in a row, each with a small row of black rectangles of different widths representing shot lengths. Light blue "ACCELERATING" rectangles shrinking left to right, body "Pressure, chase, countdown". Mint "DECELERATING" rectangles growing left to right, body "Release, relief, aftermath". Peach "STACCATO" many equal short rectangles, body "Chaos, panic, montage". Lavender "LEGATO" one long rectangle, body "Calm, immersion, the long take". Bottom half: a horizontal bar labelled "OUR FILM: 30 SECONDS" divided into eight segments with widths proportional to 5, 4, 3, 2, 1.5, 1.5, 5, 8 and labels above each: "5 s wake", "4 s bathroom", "3 s stairs", "2 s bus", "1.5 s door", "1.5 s his face", "5 s the office", "8 s his face again". The first six segments are tinted light blue with a navy label beneath "ACCELERATE", the last two are tinted mint with a label beneath "RELEASE". Full-width teal banner across the bottom reading "KEY INSIGHT: Shrink the shots to build pressure, then give the audience one long shot to breathe. The release is the joke." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 5.4: The Kuleshov triad. Face, context, return, and the meaning the audience supplies.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE KULESHOV TRIAD" with a lighter mixed-case subtitle "The face does not change. The meaning does." Layout: three large rounded frames in a row joined by teal arrows, each containing a simple black line illustration. Frame 1, light blue border, label above "SHOT 6, 1.5 s": a man's face in close-up, wide-eyed, mouth slightly open, caption below "AUDIENCE READS: panic". Frame 2, peach border, label above "SHOT 7, 5 s": a wide empty office with chairs pushed in and a small figure vacuuming and waving, caption below "AUDIENCE READS: wait...". Frame 3, mint border, label above "SHOT 8, 8 s": the identical man's face in close-up, caption below "AUDIENCE READS: relief". Beneath the frames, a small navy note: "The two close-ups are the same expression. Do not change it." Beneath that, a wide light grey card reads "Kuleshov, around 1918: one close-up cut against soup, a coffin and a woman. Audiences praised three performances. There was one." Full-width teal banner across the bottom reading "KEY INSIGHT: One extra shot, no acting, all the emotion. Put the context between two identical faces." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 5.5: The sound layer cake, and the one bridge that turns eight clips into a chase.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE SOUND LAYER CAKE" with a lighter mixed-case subtitle "Four layers, and the bridge that glues the cuts". Layout: left half, four stacked horizontal rounded bars like layers of a cake, from top to bottom: rose "DIALOGUE" "none today", peach "FOLEY: EVENT SOUNDS" "toothbrush cup, footsteps, bus doors, the switch of a laugh", mint "AMBIENCE: BACKGROUND SOUNDS" "a single bird, running water, the vacuum's hum", lavender "SCORE" "none today: the rhythm is the music". A small navy label at the left of the top three bars reads "DIEGETIC" and at the left of the bottom bar "NON-DIEGETIC". Right half: a light grey card containing a small timeline of two shot blocks labelled "STAIRS" and "BUS" with a teal sound-wave line that starts under the end of the STAIRS block and continues into the BUS block, labelled "AIR BRAKE HISS" and a navy tag "J-CUT: sound arrives before its picture". Beneath, a small card reads "Write it as an event: 'the hiss of bus air brakes begins before the cut.'" Full-width teal banner across the bottom reading "KEY INSIGHT: Name every sound the audience should hear, name the ones they should not, and let one sound cross a cut." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 5.6: Generated shot versus editing shot. One generation, eight windows, eight cuts.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "GENERATED SHOT VS EDITING SHOT" with a lighter mixed-case subtitle "One generation can contain a whole scene". Layout: a wide light grey rounded bar across the upper middle labelled "ONE GENERATED SHOT: 30 SECONDS, ONE PROMPT". Directly beneath it, the same width divided into eight rounded segments of widths proportional to 5, 4, 3, 2, 1.5, 1.5, 5, 8, alternating light blue and mint, each labelled with a tiny black line icon and a word: "bed", "mirror", "stairs", "bus", "door", "face", "office", "face". Small navy scissors icons sit on each boundary between segments with the label beneath the row "EDITING SHOTS: a cut at every window boundary". Beneath that, three small cards in a row: peach "TOKEN AT THE START: 'Hard cut.' opens every window", lavender "SAME MAN THROUGHOUT: name his face, hair and clothes once", rose "NO SOFTENING: 'no dissolves, no fades' in constraints". Full-width teal banner across the bottom reading "KEY INSIGHT: You are not asking for a video. You are handing the model an edit decision list." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

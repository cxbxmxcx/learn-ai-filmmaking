# Day 1: One Shot, One Story

*A remote worker determined to look all-business on Monday's status call takes it from the kiddie pool in her backyard, and only the camera knows.*

Watch: https://cxbxmxcx.github.io/learn-ai-filmmaking/day-1-one-shot-one-story/

## The generation prompt

Model endpoint on fal: `bytedance/seedance-2.5/text-to-video`. Seed returned: `1353173927`.

```
Settings
Model: Seedance 2.5, text-to-video, no reference images
Duration: 12 seconds
Aspect ratio: 16:9
Resolution: 720p
Audio: on
Seed: any (write it down if you like the result)

Prompt
A woman in a navy blazer with her hair in a tight bun nods seriously into a laptop on a video call, framed in a medium close-up from the shoulders up against a sunlit green hedge, and a slow, steady pull-back over twelve seconds reveals that she is sitting waist-deep in an inflatable kiddie pool in her backyard.

[0 to 4 seconds] Tight medium close-up, eye level, 35mm lens, shallow depth of field. She listens, nods twice, and types a quick note just below the bottom edge of the frame. Only her face, her blazer, the hedge and a slice of blue sky are visible. Nothing else is in frame.

[4 to 9 seconds] The camera pulls straight back at a slow, constant speed. The laptop on a white folding table enters the frame, then the rounded blue rim of the inflatable pool, then the water at her waist and her bare feet.

[9 to 12 seconds] Wide shot of the whole backyard: mown lawn, a lawn sprinkler ticking in the background, a pink flamingo floatie drifting across the foreground. Without looking away from the laptop, she reaches down, lifts a tall drink with a paper umbrella, sips, and keeps nodding professionally.

Style: bright midday summer sun, soft natural fill, warm skin tones, light film grain, a barely perceptible handheld drift, the color of a good phone photo rather than a commercial.

Audio: suburban birdsong, a lawn sprinkler ticking, water lapping softly, faint tinny voices from the laptop speaker, no music, no spoken dialogue.

Constraints: one continuous shot with no cuts, one person only, no other people, no readable text and no visible laptop screen, the pool and the water must not appear in the first four seconds, no camera shake, no identity change, no extra limbs, no jitter.
```

## Infographic prompts (Nano Banana Pro, 16:9, 2K)

### Figure 1.1: The series ladder. Each article adds one layer of control; this article is the bottom rung.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "SEVEN PROMPTS, SEVEN FILMS" with a lighter mixed-case subtitle "Each article adds one layer of directorial control". Layout: seven rounded pastel cards arranged as an ascending staircase from bottom-left to top-right, connected by short teal arrows. Card 1, light blue with a thicker border and a small teal tag reading "YOU ARE HERE": label "1 THE SHOT", body text "Size, angle, one move, one beat". Card 2, peach: "2 THE LOOK", "Light, lens, grade". Card 3, mint: "3 THE CAMERA", "Movement, blocking, the continuous take". Card 4, lavender: "4 THE CHARACTER", "References, beats, dialogue". Card 5, rose: "5 THE CUT", "Coverage, rhythm, sound". Card 6, light teal: "6 THE EFFECT", "The ten pillars". Card 7, light grey: "7 THE DIRECTOR'S PROMPT", "Everything in one generation". Each card carries one simple black line icon: a single film frame, a light bulb, a camera on a dolly, a person silhouette, scissors over a film strip, a burst of particles, a clapperboard. A thin navy label under the staircase reads "NOVICE" at the far left and "EXPERT" at the far right. Full-width teal banner across the bottom reading "KEY INSIGHT: Film craft first, prompt second. Every layer you add is a layer of control you keep." in white. Legible sans-serif type, thin matching borders on every card, no gradients, no 3D, no photographic textures.
```

### Figure 1.2: The shot-size ladder, from widest to tightest, and what each size does to the viewer.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE SHOT-SIZE LADDER" with a lighter mixed-case subtitle "Shot size is emotional distance". Layout: six rounded pastel cards in one row from left to right, each containing a simple black line drawing of the same standing figure framed progressively tighter inside a small rectangle. Card 1, light blue, label "EXTREME WIDE", a tiny figure in a landscape, body text "Here is the world". Card 2, mint, "WIDE", full body head to feet, "Here is where we are". Card 3, peach, "MEDIUM", waist up, "Here is a person". Card 4, lavender, "MEDIUM CLOSE-UP", chest up, "Here is what they mean". Card 5, rose, "CLOSE-UP", the face, "Here is what they feel". Card 6, light teal, "EXTREME CLOSE-UP", the eyes only, "Here is the detail that matters". A long teal arrow runs beneath the row from left to right labelled "CLOSER TO THE VIEWER". Below the arrow, one wide light grey card reads "PROMPTING RULE: the tighter the shot, the shorter the description". Full-width teal banner across the bottom reading "KEY INSIGHT: Choose the distance before you choose the words." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 1.3: From logline to frame. Every story element has to become something the lens can see or the microphone can hear.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "FROM LOGLINE TO FRAME" with a lighter mixed-case subtitle "If the camera cannot see it, the model cannot make it". Layout: two columns of five stacked rounded cards, each left card joined to its right partner by a teal arrow. Left column header in navy: "THE LOGLINE". Left cards: light blue "PROTAGONIST" with body "A remote project manager on Monday's status call"; mint "GOAL" with "Look like the most buttoned-up person on the team"; peach "INCITING INCIDENT" with "The first hot day of summer"; rose "CONFLICT" with "She is in the pool"; lavender "HOOK" with "Only the camera knows". Right column header in navy: "WHAT THE CAMERA SEES". Right cards in matching colors: "Navy blazer, hair in a bun, nodding at a laptop"; "Serious eye contact, small nods, typing"; "Hard midday sun, blue sky, green hedge"; "Bare feet in blue water, inflatable pool, flamingo floatie"; "A slow pull-back that reveals everything in order". Between the columns, one line of navy text: "A logline you can film is a logline you can prompt". Simple black line icons on the left cards: a person, a target, a sun, a wave, a magnifying glass. Full-width teal banner across the bottom reading "KEY INSIGHT: Translate every story element into something visible or audible before you write a single prompt word." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 1.4: The frame is information. One pull-back, three states of knowledge.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE FRAME IS INFORMATION" with a lighter mixed-case subtitle "What the audience knows, second by second". Layout: three large rounded frames in a row, each holding a simple black line illustration of the same scene at a different framing, with a time label above each frame and a caption below it. Frame 1, light blue border, label "0 TO 4 SECONDS": tight framing of a woman in a blazer from the shoulders up against a hedge, caption "AUDIENCE KNOWS: office". Frame 2, peach border, label "4 TO 9 SECONDS": wider framing, a laptop on a folding table and the rim of an inflatable pool now visible, caption "AUDIENCE KNOWS: something is off". Frame 3, mint border, label "9 TO 12 SECONDS": wide backyard, the woman waist-deep in a kiddie pool, a flamingo floatie, a sprinkler, a drink with a paper umbrella, caption "AUDIENCE KNOWS: the joke". One long teal arrow runs beneath all three frames labelled "ONE CONTINUOUS PULL-BACK". A small lavender card at the bottom left reads "MOTIVATED MOVE: the camera moves because the story needs the reveal". Full-width teal banner across the bottom reading "KEY INSIGHT: A reveal is three frames and one move. Describe all three." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

Correction appended for the published take:

```
Story continuity matters: it is the same woman in all three frames, with dark hair pulled back in a tight bun and a blazer, and she is sitting INSIDE the inflatable pool in all three frames; the frames only differ in how wide the framing is. In frame 2 she must NOT sit on a chair and her legs must not be visible: show her from the waist up behind a white folding table that holds the open laptop, with the rounded blue rim of the inflatable pool entering across the bottom of the frame in front of her. In frame 3 keep the same white folding table and laptop in front of her at the pool. No logo on the laptop and no coffee mug. Layout: place the small lavender MOTIVATED MOVE card centered horizontally, directly under the long teal arrow, with clear empty space below it. The full-width teal KEY INSIGHT banner sits at the very bottom edge of the image, nothing overlaps it, and its text is centered.
```

### Figure 1.5: Anatomy of a video prompt, in the order the model reads it.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "ANATOMY OF A VIDEO PROMPT" with a lighter mixed-case subtitle "What the model reads, in the order it reads it". Layout: six connected rounded pastel boxes in a single row with teal arrows between them and a simple black line icon above each. Box 1, light blue, label "SUBJECT", body "A woman in a navy blazer, hair in a bun", icon a person. Box 2, mint, "ACTION", "Nodding seriously into a laptop on a video call", icon a laptop. Box 3, peach, "ENVIRONMENT", "Sunlit hedge, then a backyard with a kiddie pool", icon a sun over a hedge. Box 4, lavender, "CAMERA", "Medium close-up to wide, slow steady pull-back, eye level, 35mm", icon a camera on a dolly. Box 5, rose, "STYLE AND SOUND", "Midday sun, light grain, birds, sprinkler, no music", icon a speaker. Box 6, light grey, "CONSTRAINTS", "One shot, one person, no text, pool hidden for four seconds", icon a checklist. A thin navy bracket above the first two boxes labelled "THE FIRST SENTENCE CARRIES THE MOST WEIGHT". A wider bracket beneath all six boxes labelled "ONE GENERATION PROMPT". Beneath that bracket, three small light teal cards in a row reading "[0 to 4 s]", "[4 to 9 s]", "[9 to 12 s]" with a navy label "TIME WINDOWS". Full-width teal banner across the bottom reading "KEY INSIGHT: Lock who and what in the first sentence; direct everything else after it." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 1.6: The one-shot workflow. The same loop runs for every film in the series.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE ONE-SHOT WORKFLOW" with a lighter mixed-case subtitle "The loop you will run for every film in this series". Layout: six rounded pastel cards arranged in a circle, connected clockwise by curved teal arrows, starting at the top. Card 1, light blue, label "LOGLINE", body "Five elements, one sentence". Card 2, mint, "BEAT", "Person, want, obstacle, turn". Card 3, peach, "SHOT SPEC", "Size, angle, move, duration, sound". Card 4, lavender, "PROMPT", "Subject first, then time windows, style, sound, constraints". Card 5, rose, "GENERATE", "12 s, 16:9, 720p, audio on". Card 6, light teal, "JUDGE", "Check the spec, not your hopes". In the center of the circle one light grey card reads "CHANGE ONE THING PER TAKE". Simple black line icons on each card: a pencil, a heart, a table grid, a document, a play button, a magnifying glass. Full-width teal banner across the bottom reading "KEY INSIGHT: If two takes disagree, the prompt is under-specified, not the model." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

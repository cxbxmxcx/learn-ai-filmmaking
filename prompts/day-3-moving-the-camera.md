# Day 3: Moving the Camera

*A waiter carries a sparkler-topped dessert through a packed restaurant to a birthday guest who turns out to be a hundred years old, and she blows it out in one breath.*

Watch: https://cxbxmxcx.github.io/learn-ai-filmmaking/day-3-moving-the-camera/

## The generation prompt

Model endpoint on fal: `bytedance/seedance-2.5/text-to-video`. Seed returned: `318308462`.

```
Settings
Model: Seedance 2.5, text-to-video, no reference images
Duration: 20 seconds
Aspect ratio: 16:9
Resolution: 720p
Audio: on
Seed: any (write it down if you like the result)

Prompt
A waiter in a black apron carries a slice of cake topped with a lit sparkler through a packed, noisy bistro, the camera tracking close behind his shoulder as he weaves between tables, then arcing around him as he reaches a long table to reveal the birthday guest, a tiny hundred-year-old woman in a gold paper crown, who blows out the sparkler in one breath and takes a bow.

Look: 35mm, shallow depth of field, 24 fps, fine 35mm film grain, warm tungsten restaurant light with practical candles on the tables, natural skin tones, a real neighborhood bistro on a Friday night, not a commercial.

[0 to 7 seconds] Tracking shot from just behind the waiter's right shoulder, steadicam-smooth, moving at walking pace through the crowded dining room. The sparkler throws flickering white light on his sleeve. Diners glance up as he passes; wine glasses, table edges and the backs of other waiters slide past in the foreground.
[7 to 13 seconds] As he reaches the long table, the camera arcs around his left side in one smooth curve, keeping the sparkler in frame, and comes to rest facing the table: a family of six leaning in, and at the center a tiny hundred-year-old woman in a gold paper crown, eyes bright, hands folded. The waiter sets the plate down in front of her.
[13 to 20 seconds] The camera settles into a slow push-in to a medium close-up on her. She inhales, blows out the sparkler in one long breath, the light dies to a wisp of smoke, she raises both hands and takes a seated bow, and the whole restaurant erupts in applause and cheering behind her.

Audio: dense restaurant chatter and cutlery on plates, the sparkler's fizzing hiss growing louder as we approach the table, a hush as she inhales, one long breath, then a room-wide burst of applause and cheering. No music, no dialogue.

Constraints: one continuous shot with no cuts, the camera never stops moving until the final push-in, the birthday guest is not visible until the arc begins, the sparkler stays in frame for the whole shot, no readable text, no identity change, no extra limbs, no jitter.
```

## Infographic prompts (Nano Banana Pro, 16:9, 2K)

### Figure 3.1: Camera movement vocabulary. Twelve moves, what each does, and the word to use for it.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "CAMERA MOVEMENT VOCABULARY" with a lighter mixed-case subtitle "Twelve moves a model already knows by name". Layout: a grid of twelve rounded pastel cards, four columns by three rows, each with a simple black line diagram of a camera icon and a teal arrow showing the move, an all-caps label and one short line. Row 1: light blue "PAN", horizontal arrow, "Swivel left or right from a fixed spot. Survey, follow."; light blue "TILT", vertical arrow, "Swivel up or down. Reveal height, look down."; mint "DOLLY", arrow toward the subject, "Camera moves closer or further. Draw in, release."; mint "TRACKING", arrow alongside a walking figure, "Camera travels with the subject. Journey." Row 2: peach "ARC", curved arrow around a figure, "Camera circles the subject. Reveal, intimacy."; peach "CRANE", arrow rising, "Camera lifts or descends. Scale, grandeur."; lavender "PUSH IN", short arrow toward a face, "Slow move closer. Emotion, realization."; lavender "PULL BACK", short arrow away from a face, "Slow move away. Context, the reveal." Row 3: rose "WHIP PAN", blurred fast arrow, "Very fast pan. Energy, transition."; rose "RACK FOCUS", two circles with focus shifting, "Focus changes subject. Attention."; light teal "HANDHELD", jittery small arrows, "Human unsteadiness. Urgency, realism."; light teal "STEADICAM", smooth wavy arrow, "Floating smooth follow. Immersion." Full-width teal banner across the bottom reading "KEY INSIGHT: Name the move, the speed and where it ends. A move without an end point is a drift." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 3.2: Motivated and unmotivated movement. Four reasons to move, and the drift that has none.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "WHY THE CAMERA MOVES" with a lighter mixed-case subtitle "Four reasons, and the one that is not a reason". Layout: four rounded pastel cards in a row across the top, each with a black line icon and a short example. Light blue "FOLLOW" icon of a camera trailing a walking figure, body "We travel with the waiter through the room". Mint "DISCOVER" icon of a camera panning across three objects, body "We find the table one detail at a time". Peach "REVEAL" icon of a camera arcing to expose a hidden figure, body "The arc shows us who the dessert is for". Lavender "EMPHASIZE" icon of a camera pushing toward a face, body "The push-in says: watch her now". Beneath the row, one wide rose card with an icon of a camera floating with no target and the text "THE DRIFT: slow, weightless, toward nothing. Audiences read it as nobody directing. If a move has no reason, hold still." Beneath that, a small light grey card reads "Test: finish the sentence 'the camera moves so that the audience...' If you cannot, cut the move." Full-width teal banner across the bottom reading "KEY INSIGHT: A motivated move is a sentence with a purpose. A drift is a sentence with no verb." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 3.3: Blocking the restaurant from above. The waiter's path, the camera's path, and the three moves.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "BLOCKING THE RESTAURANT" with a lighter mixed-case subtitle "Draw the room from above before you write a word". Layout: a large rounded light grey card filling most of the page containing a top-down floor plan drawn in simple black lines: a kitchen door at the left edge, eight round tables with small chair circles scattered across the room, and one long rectangular table at the right with six chairs. A solid orange line marks the waiter's path from the kitchen door weaving between the round tables to the head of the long table, with a small figure icon at the end. A dashed teal line marks the camera's path, running just behind the orange line, then curving in a half circle around the waiter at the long table, then a short straight segment toward the head of the table. Three numbered navy circles sit on the teal line: "1" near the kitchen door, "2" at the start of the half circle, "3" at the end of the short segment. A legend in the bottom left corner of the card: orange line "WAITER", dashed teal line "CAMERA", navy circle "MOVE CHANGES". To the right of the floor plan, three small stacked cards: light blue "1 TRACK: behind his shoulder, walking pace, 0 to 7 s", peach "2 ARC: half circle around his left side, 7 to 13 s", mint "3 PUSH IN: settle to a medium close-up on the guest, 13 to 20 s". Full-width teal banner across the bottom reading "KEY INSIGHT: If you cannot draw the camera's path, the model cannot walk it." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 3.4: The three-part move, and how three of them chain into one take.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "THE THREE-PART MOVE" with a lighter mixed-case subtitle "Start framing, the move, end framing. Then chain them." Layout: top half, three rounded cards in a row joined by teal arrows: light blue "START FRAMING" body "Where the camera is and what fills the frame", peach "THE MOVE" body "Name it, give it a speed, give it a side", mint "END FRAMING" body "Where it stops and what it now shows". Bottom half: a horizontal timeline bar from 0 to 20 seconds divided into three colored segments with labels above: light blue segment "0 to 7 s TRACK behind the waiter, walking pace", peach segment "7 to 13 s ARC around his left, one smooth curve", mint segment "13 to 20 s PUSH IN, settles on the guest". Small navy text under the joins reads "end of one = start of next". Beneath the timeline, four small light grey cards with pace words: "walking pace", "one smooth curve", "settles into", "holds". Full-width teal banner across the bottom reading "KEY INSIGHT: Give every move an end point and a speed, and hand each end point to the next move." in white. Legible sans-serif type, thin matching borders, simple black line icons, no gradients, no 3D, no photographic textures.
```

### Figure 3.5: One take or three shots. When the moves carry the story, and when a cut serves it better.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "ONE TAKE OR THREE SHOTS?" with a lighter mixed-case subtitle "A decision tree for every scene". Layout: a simple top-down flowchart of rounded cards joined by teal arrows. Top card, light grey: "Does the camera's journey carry the story?" Two arrows labelled "YES" and "NO". YES leads to a mint card "Can each move hand a reason to the next?" with YES to a light blue card "ONE CONTINUOUS TAKE: consistent look, light and character; write three-part moves and chain them" and NO to a rose card "Cut the move that has no reason, then reconsider". NO from the top leads to a peach card "Does the story need two places at once?" with YES to a lavender card "CUT: coverage and rhythm, see Article 5" and NO to a light teal card "HOLD STILL: a locked-off frame and light, see Article 2". At the bottom, a small navy note: "Our restaurant: the walk is the suspense, the arc is the punchline, so one take." Full-width teal banner across the bottom reading "KEY INSIGHT: A long take is a promise that every move matters. Only make it when you can keep it." in white. Legible sans-serif type, thin matching borders, no gradients, no 3D, no photographic textures.
```

### Figure 3.6: Driving the camera with a video. The advanced path when words are not precise enough.

```
Flat, clean educational infographic, 16:9, off-white background (#F4F8FB). Bold all-caps navy title "DRIVING THE CAMERA WITH A VIDEO" with a lighter mixed-case subtitle "When the move has to be exact, show it instead of describing it". Layout: four rounded pastel cards in a row joined by teal arrows. Light blue "1 RECORD THE MOVE" icon of a phone, body "Walk the path with a phone, or animate a grey 3D blockout, 5 to 20 seconds". Mint "2 ATTACH IT" icon of a paperclip, body "Add the clip as a video reference alongside the prompt". Peach "3 BIND IT" icon of a chain link, body "Tell the model: use the video for camera movement only, not for people or place". Lavender "4 GENERATE" icon of a play button, body "The model matches the path, speed and framing of your clip". Beneath the row, a wide light grey card reads "The text version works for most scenes. Reach for a video reference when a move keeps failing or must match another shot exactly." Full-width teal banner across the bottom reading "KEY INSIGHT: A video reference is a dolly track you can draw with your feet." in white. Legible sans-serif type, thin matching borders, simple black line icons, no gradients, no 3D, no photographic textures.
```

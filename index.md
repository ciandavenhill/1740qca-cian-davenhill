---
layout: default
title: 1740QCA Cian Davenhill
---

# 1740QCA Cian Davenhill
### Process Journal — Fundamentals of Moving Image

Quick navigation: [Task 01](#task-01) · [Task 02](#task-02) · [Task 03](#task-03) · [Task 04](#task-04) · [Task 05](#task-05) · [Task 06](#task-06)

---

## Task 01: Image Database Creation
<a name="task-01"></a>

Before any capturing or editing began, I built a structured file directory to keep RAW captures, working PSDs, and exports separate and traceable throughout the project. Keeping this consistent from week one meant every later task — Lightroom catalogues, Photoshop exports, After Effects source folders — could reference a predictable location.

![Folder structure screenshot](images/task01-folder-structure.jpg)
*Correctly named sub-folder structure separating RAW captures, PSD working files, and final exports — the foundation for every task that follows.*

---

## Task 02: Capture, Import, Edit & Export
<a name="task-02"></a>

This task focused on getting comfortable with a full RAW workflow: capturing, cataloguing, and non-destructively editing images in Lightroom Classic before exporting them for use in Photoshop.

![Lightroom Develop module screenshot](images/task02-develop-module.jpg)
*Develop module showing experimentation with exposure, contrast, white balance, and tone curve adjustments on a RAW capture.*

![Before/after edit](images/task02-before-after.jpg)
*Before and after comparison — pushed the HSL panel (targeting specific hue ranges), added clarity, and applied a custom user preset to establish a consistent look across the sequence.*

![Lightroom catalogue screenshot](images/task02-catalogue.jpg)
*Completed Lightroom Classic catalogue file, along with a back-up catalogue, ensuring the image database remained recoverable and intact.*

---

## Task 03: The Composite Image
<a name="task-03"></a>

For this task I moved into Photoshop's Layers panel to build a set of composite images, deliberately varying my approach across each one — different mask types, blend modes, and adjustment layer combinations — rather than repeating a single technique.

### Composite 1 — Gradient Blend with Vivid Light
![Composite 1](images/task03-composite-01.jpg)
*Built by grouping a base layer with a second exposure, blended using a gradient layer mask and set to Vivid Light for a high-contrast, punchy result. A clipped Curves adjustment layer targeted local contrast, while an unclipped Hue/Saturation layer unified the colour grade across the whole composite.*

![Layers panel — Composite 1](images/task03-composite-01-layers.jpg)
*Layers panel showing the grouped composite structure: gradient mask, Vivid Light blend mode, a clipped Curves adjustment, and a global Hue/Saturation pass sitting above the group.*

### Composite 2 — Black & White with Film Grain
![Composite 2](images/task03-composite-02.jpg)
*Converted using a Black & White adjustment layer with channel-specific tonal control (rather than a flat desaturation), boosted with a Curves S-curve for contrast. Film grain was added via a 50%-grey Overlay layer with monochromatic noise applied, and a soft elliptical vignette mask was used to draw focus toward the centre of the frame.*

![Layers panel — Composite 2](images/task03-composite-02-layers.jpg)
*Layers panel showing the Black & White and Curves adjustment layers, the grain layer set to Overlay, and the inverted, feathered vignette mask.*

### Composite 3 — Ghosting / Double Exposure
![Composite 3](images/task03-composite-03.jpg)
*Created by duplicating the base layer, setting the duplicate to Screen blend mode, and offsetting it slightly to produce a soft double-exposure "echo." A gradient mask controlled where the ghosting effect appeared, fading it into the sky rather than applying it evenly across the frame, and layer opacity was reduced to keep the effect atmospheric rather than overpowering.*

![Layers panel — Composite 3](images/task03-composite-03-layers.jpg)
*Layers panel showing the duplicated and offset layer, Screen blend mode, gradient mask, and opacity adjustment.*

### Composite 4 — Split-Tone Cinematic Grade
![Composite 4](images/task03-composite-04.jpg)
*Built entirely through adjustment layers rather than masking: a base Curves S-curve for contrast, followed by two separate Color Balance layers — one targeting shadows (pushed toward cyan/blue) and one targeting highlights (pushed toward red/yellow) — to produce a teal-and-orange cinematic look.*

![Layers panel — Composite 4](images/task03-composite-04-layers.jpg)
*Layers panel showing the Curves layer and the two independently targeted Color Balance adjustment layers, grouped as "Cinematic_split_tone."*

---

## Task 04: The GIF — Looping Moving Image
<a name="task-04"></a>

Rather than animating a fresh photo sequence, I used my Task 03 composite file directly: toggling layer visibility, masks, and blend modes between frames in Photoshop's Timeline panel to create a shifting, glitch-like portrait animation — reinforcing the same layer techniques from Task 03 in a temporal context.

### GIF 1 — Fast, flickering rhythm
![GIF 1](images/task04-gif-01.gif)
*Short frame duration (0.1s) with no tweening, toggling mask and blend mode visibility between frames for a fast, stuttering, flicker-like effect.*

### GIF 2 — Slow, dissolving rhythm
![GIF 2](images/task04-gif-02.gif)
*Longer frame duration (0.4–0.5s) with tweening applied between key frames, letting Photoshop interpolate position and opacity for a smoother, dreamier transition between layer states.*

### GIF 3 — Looping variation
![GIF 3](images/task04-gif-03.gif)
*A third pass using Forever looping with a mixed duration pattern across frames, to compare pacing and rhythm side-by-side with GIFs 1 and 2.*

![Timeline panel screenshot](images/task04-timeline.jpg)
*Timeline panel showing individual frame durations and the tweening dialog used to generate in-between frames.*

![Export settings screenshot](images/task04-export-settings.jpg)
*Save for Web (Legacy) export settings — GIF format, reduced colour palette and dimensions to keep file size manageable for web playback.*

---

## Task 05: Image Sequences in After Effects
<a name="task-05"></a>

For this task I built a stop-motion image sequence, imported it into After Effects as individual layers (not a single merged sequence, so each frame remained independently editable), and produced five compositions from the same source material — each varying still duration, layer overlap, and transition type to explore how temporal pacing changes the feel of the same footage.

### Composition 1 — Baseline, no transition
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID_1" title="YouTube video player" frameborder="0" allowfullscreen></iframe>

*Still duration of 4 frames per image, no overlap, no transition — a straightforward, evenly-paced cut between stills as a baseline for comparison.*

### Composition 2 — Dissolve transition, short overlap
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID_2" title="YouTube video player" frameborder="0" allowfullscreen></iframe>

*Still duration of 4 frames, 2-frame overlap using the Dissolve Front Layer transition — softening the cut between stills without fully blending them.*

### Composition 3 — Longer hold, deeper dissolve
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID_3" title="YouTube video player" frameborder="0" allowfullscreen></iframe>

*Still duration extended to 8 frames with a 4-frame overlap, still using Dissolve Front Layer — a noticeably slower, more deliberate pace than Composition 2.*

### Composition 4 — Fast, punchy pacing
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID_4" title="YouTube video player" frameborder="0" allowfullscreen></iframe>

*Still duration reduced to 2 frames, no overlap, no transition — the fastest-paced composition in the set, producing a rapid, almost frantic stop-motion rhythm at the opposite extreme to Composition 3.*

### Composition 5 — Slow, blended dissolve
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID_5" title="YouTube video player" frameborder="0" allowfullscreen></iframe>

*Still duration of 12 frames with an 8-frame overlap, using Cross Dissolve Front and Back Layers so both outgoing and incoming stills blend together — the slowest and most atmospheric composition of the five.*

![Timeline and Composition panel](images/task05-timeline-composition.jpg)
*Timeline panel showing sequenced layers with overlap keyframes, alongside the corresponding frame in the Composition panel.*

---

## Task 06: Reflective Report
<a name="task-06"></a>

*[Write your ~300-word reflective report here once Tasks 01–05 are finalised. Use the Self Evaluation Form to identify genuine strengths and challenges before writing. Structure suggestion:*

*1. What technical skills you can now do that you couldn't before (be specific — name techniques, not software).*
*2. A real challenge you hit and how you solved it (e.g. troubleshooting a hidden layer/mask, working out After Effects overlap settings, or a technique — like Quick Selection masking — that didn't work as expected and what you switched to instead).*
*3. Critical evaluation of your outcomes — what worked aesthetically and why, using correct terminology (tweening, temporal rhythm, clipping mask, still duration, cross dissolve, etc.).*
*4. A brief forward-looking note on what you'd explore further.]*

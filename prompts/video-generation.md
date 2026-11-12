# Video Generation Prompts

[← Prompt Library](README.md)

Use these with the tools in [Free Video Generators](../docs/free-video-generators.md). Generate AI clips as **B-roll inside an edited video**, not as the whole video.

---

## 1. Script → shot list

```
Here is my voiceover script with [visual directions]: {paste script}

Create a shot list as a table: timestamp | narration line | shot type
(AI video / AI image / stock footage / text-motion graphic / map / chart) |
shot description | duration (3-6 s).
Change the visual every 3-6 seconds. Mark which shots MUST be AI-generated
vs. which can come from free stock libraries.
```

## 2. Shot → AI video prompt

```
Convert each shot description below into a prompt for an AI text-to-video model
(5-second clip, 16:9). For each, specify:
- Subject and action (one clear action only)
- Camera movement (slow dolly in, aerial pan, static, handheld)
- Lighting and mood
- Visual style (cinematic, documentary, 3D animation, watercolour), consistent across
  all shots: {style}
- What to avoid (text, logos, real identifiable people, distorted hands)

SHOTS:
{paste shots}
```

## 3. Consistent style guide

```
Create a one-paragraph "visual style bible" for my faceless channel about {niche}
that I can paste at the end of every AI image/video prompt so all visuals look like
one brand. Include colour palette, lighting, camera language, texture/grain, and mood.
```

## 4. Image → video (animate a still)

```
I have a still image of: {describe image}.
Write 3 image-to-video motion prompts (5 s each) that animate it subtly and
realistically: e.g. parallax camera move, environmental motion (smoke, water,
clouds), small subject movement. Keep the subject's identity and composition stable.
```

## Template: single video prompt

```
[Subject] [doing one action], [setting], [time of day / lighting],
[camera movement], [lens/shot type], [style], [mood], 16:9,
no text, no logos, no watermarks
```

**Example:**
`An old cargo ship sailing through stormy seas, North Atlantic, dusk with lightning, slow aerial tracking shot, wide angle, cinematic documentary style, tense mood, 16:9, no text, no logos, no watermarks`

# Scripting Prompts

[← Prompt Library](README.md)

---

## 1. Research brief

```
Create a research brief for a YouTube video titled "{title}".
Audience: {audience}. Length: {8-12} minutes.

Include: the core question the video answers, 8-12 key facts (each with the type of
source I should verify it against), 3 surprising angles most videos on this topic miss,
and common misconceptions. Mark anything you are not certain of as [VERIFY].
```

## 2. Outline with retention structure

```
Using this research brief: {paste brief}

Write an outline for a {length}-minute faceless YouTube video titled "{title}".
Structure:
- Hook (0:00-0:30): deliver on the title's promise immediately and open a curiosity loop
- Context (why this matters now)
- 4-6 main sections, each ending with a re-hook / open loop into the next
- Payoff: the strongest insight saved for near the end
- Outro: one-line CTA to a related video (no "smash that like button")
Add [B-ROLL] suggestions for each section.
```

## 3. Hook writer (5 options)

```
Write 5 different 30-second hooks (~75-90 words each) for a video titled "{title}"
about {topic}. Use different styles: contrarian, story/in-medias-res, shocking statistic,
question, and "you've been told X, but...". Each hook must confirm the viewer clicked
the right video within the first sentence.
```

## 4. Full script

```
Write the full voiceover script from this outline: {paste outline}

Rules:
- Conversational, spoken English: short sentences, active voice, no filler
- {word count} words (~150 words per minute)
- Every 60-90 seconds, add a pattern interrupt (question, twist, or new visual idea)
- Put visual directions in [square brackets] on their own lines
- Mark any factual claim I must verify with [VERIFY]
- Write in this tone: {e.g. calm documentary narrator / energetic explainer}
```

## 5. Script review (use a fresh chat)

```
Act as a harsh YouTube script editor. Review the script below for:
1. Hook strength: would a viewer stay past 30 seconds? Why or why not?
2. Pacing: list any section that drags
3. Factual claims that need sources
4. Anything that sounds generic or AI-written, quoted, with a rewrite
5. Risk of looking like templated "inauthentic" content
Score it 1-10 and give the 5 highest-impact fixes.

SCRIPT:
{paste script}
```

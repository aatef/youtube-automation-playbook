# Titles, Thumbnails & Metadata Prompts

[← Prompt Library](README.md)

---

## 1. Title options

```
Generate 15 YouTube titles for a video about {{topic}} for {{audience}}.
Constraints: under 60 characters, no clickbait the video can't deliver, front-load the
most interesting words. Use a mix of formulas: curiosity gap, "How X did Y",
"Why X", number/list, contrarian, and outcome-based.
Then pick the top 3 and explain why each would get a high CTR.
```

## 2. Thumbnail concepts

```
Video title: "{{title}}". Niche: {{niche}}. Channel style: {{e.g. dark, minimal, bold yellow text}}.

Give me 4 thumbnail concepts. For each describe:
- Focal point (one main subject)
- Background and colour contrast
- Text overlay (max 4 words, and must NOT repeat the title)
- The curiosity or emotion it creates together with the title
Keep it readable at mobile size. No real people's faces.
```

## 3. Thumbnail image prompt (for AI image tools)

```
Turn this thumbnail concept into a detailed image-generation prompt for a 16:9
YouTube thumbnail: {{concept}}.
Specify subject, composition (rule of thirds, leave space for text on the {{left/right}}),
lighting, colour palette, style ({{photorealistic / 3D render / illustrated}}), and
high contrast. Do NOT include text in the image; I'll add it in the editor.
```

## 4. Description, chapters & tags

```
Write YouTube metadata for this video.
Title: {{title}}
Script: {{paste script}}

Provide:
1. Description: first 2 lines are a compelling summary with the main keyword
   (shown above "...more"), then a 120-word overview, then placeholders for links
2. Chapters with timestamps (estimate at 150 words/minute, first chapter 0:00)
3. 10-15 tags (mix of broad and specific)
4. 3 hashtags
5. A pinned comment that asks viewers a specific question about the topic
```

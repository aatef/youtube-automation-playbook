# 🤖 YouTube with AI: Claude + Higgsfield & More

[← Back to README](../README.md)

Use **Claude** as the brain (research, scripts, planning) and plug in AI tools through **MCP connectors**, so Claude can generate the videos, images and voice for you from one chat.

```
You (idea) → Claude (research + script + scene plan) → Higgsfield MCP (images, video, audio) → ElevenLabs (voice) → Edit & publish
```

> ⚠️ Automation makes production faster, but you still own the judgement: pick the angle, fact-check, and review every video. See the [AI Usage Guide](ai-usage.md) for YouTube's inauthentic-content and AI-disclosure rules.

---

## 🎥 Video guides

Videos come from two channels: **[Danny Why](../people/danny-why.md)** and **[Beyond Tahir](../people/beyond-tahir.md)**.

### Danny Why: Claude + Higgsfield ([@danny_why](https://www.youtube.com/@danny_why))
| # | Video | Watched |
|---|---|---|
| 1 | [Claude Literally Just Changed YouTube Forever](https://www.youtube.com/watch?v=WqXULg6uR30) | ☐ |
| 2 | [How I Use Claude Code To Grow 10x Faster On YouTube](https://www.youtube.com/watch?v=ZpbUI8b8ZT4) | ☐ |
| 3 | [Claude Fable 5 Just Changed YouTube Forever!](https://www.youtube.com/watch?v=qqhQ9QPL_CY) | ☐ |
| 4 | [Claude Code + CapCut Just Changed YouTube Forever](https://www.youtube.com/watch?v=QKdR_wo9KZY) | ☐ |
| 5 | [Claude Code Just Changed CapCut Forever!](https://www.youtube.com/watch?v=juMF6KUhOjY) | ☐ |
| 6 | [Claude Code Just Changed Making Money Online!](https://www.youtube.com/watch?v=0ht45bzJ_7w) | ☐ |
| 7 | [Claude Code Can Now Edit Your Videos in 10 Minutes](https://www.youtube.com/results?search_query=Danny+Why+Claude+Code+Can+Now+Edit+Your+Videos+in+10+Minutes) | ☐ |
| 8 | [How I Use Claude Code to Create 2D Animations (Tutorial)](https://www.youtube.com/results?search_query=Danny+Why+How+I+Use+Claude+Code+to+Create+2D+Animations) | ☐ |

### Beyond Tahir: AI tools & Claude workflows ([@beyondtahir](https://www.youtube.com/@beyondtahir))
| # | Video / resource | Watched |
|---|---|---|
| 1 | [Beyond Tahir: Claude videos (channel search)](https://www.youtube.com/@beyondtahir/search?query=claude) | ☐ |
| 2 | [Beyond Tahir Shorts: AI tips in English & Urdu](https://www.youtube.com/channel/UCTut5DNU-4GUJpylYid30kw) | ☐ |
| 3 | [BeyondArtist: Claude Code plugin for thumbnails (Autopilot)](https://github.com/beyondtahir/beyondartist) | ☐ |
| 4 | [Beyondsumi: animated storytelling videos with Claude Code, no video API](https://github.com/beyondtahir/beyondsumi) | ☐ |

> Add Beyond Tahir's specific Claude/Higgsfield videos here as you find them:
> `| 5 | [Video title](https://www.youtube.com/watch?v=VIDEO_ID) | ☐ |`

> Earnings claims in video titles are the creators' claims, not results you should expect.

---

## 🔌 Tools you can plug into Claude

| Tool | What it adds to Claude | How to connect | Cost |
|---|---|---|---|
| **[Higgsfield MCP](https://higgsfield.ai/mcp)** | Images, video, characters and audio across 30+ models from one connector | Custom connector URL: `https://mcp.higgsfield.ai/mcp` (no API key) | Uses your Higgsfield credits |
| **[ElevenLabs MCP](https://github.com/elevenlabs/elevenlabs-mcp)** | Text-to-speech, voice cloning, transcription, sound effects | ElevenLabs hosted MCP server (see their docs) | ![FREE TIER](https://img.shields.io/badge/FREE-TIER-blue) free monthly credits |
| **[Runway MCP](https://higgsfield.ai/blog/best-ai-video-mcp-servers)** | Runway video models | Connector URL / plugin, OAuth | Runway credits |
| **[HeyGen MCP](https://higgsfield.ai/blog/best-ai-video-mcp-servers)** | Avatar and translated videos | Connector URL / plugin, OAuth | Plan credits |
| **[fal.ai MCP](https://higgsfield.ai/blog/best-ai-video-mcp-servers)** | Large catalog of video, image, audio and speech models | Connector URL, OAuth or API key | Pay per use |
| **vidIQ MCP** | Channel research, outliers, video ideas, title and thumbnail help | Claude connector / plugin | vidIQ plan |
| **[BeyondArtist](https://github.com/beyondtahir/beyondartist)** by [Beyond Tahir](../people/beyond-tahir.md) | Claude Code plugin: thumbnails from a YouTube link (Autopilot), Urdu/Hindi text | Install from GitHub | ![100% FREE](https://img.shields.io/badge/100%25-FREE-brightgreen) |
| **[Beyondsumi](https://github.com/beyondtahir/beyondsumi)** by [Beyond Tahir](../people/beyond-tahir.md) | Animated Sumi-style storytelling videos without a video-generation API | Install from GitHub | ![100% FREE](https://img.shields.io/badge/100%25-FREE-brightgreen) |

---

## ⚙️ Connect Higgsfield to Claude (about a minute)

1. In Claude (web or desktop), open **Settings → Connectors** (or **Customize → Connectors**).
2. Click **Add → Add custom connector**.
3. Name it **Higgsfield** and paste: `https://mcp.higgsfield.ai/mcp`
4. Click **Connect** and sign in with your Higgsfield account.
5. In a chat, describe the video you want. Claude picks the model, or you can name one.

📖 Official guide: [How to Generate AI Videos in Claude With the Higgsfield MCP Connector](https://higgsfield.ai/blog/Generate-AI-Videos-From-Claude-with-Higgsfield-MCP)

> 💳 Every generation through the connector uses Higgsfield credits. Free and unlimited generations on higgsfield.ai don't apply through MCP.

---

## 🧭 Suggested workflow
1. **Research** with Claude (+ vidIQ): niche, outlier videos, title patterns. Use [niche-research prompts](../prompts/niche-research.md).
2. **Script** with Claude: hook, outline, full script, then review. Use [scripting prompts](../prompts/scripting.md).
3. **Scene plan**: Claude turns the script into a shot list. Use [video-generation prompts](../prompts/video-generation.md).
4. **Generate**: Claude calls Higgsfield for images and clips, and ElevenLabs for the voice.
5. **Edit**: CapCut or DaVinci Resolve (see [Free Tools](resources.md)), or Claude Code editing workflows.
6. **Package**: titles and thumbnails (BeyondArtist or [title/thumbnail prompts](../prompts/titles-thumbnails.md)).
7. **Review & publish**: fact-check, set the AI disclosure, upload.

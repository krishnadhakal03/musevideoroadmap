# 🧰 Tools — Inventory

> Last updated: 2026-10-01 (NPT)

| Tool | What it does | Used at stage |
|---|---|---|
| **Meta AI TTS** (`avocado_v2` voices) | Voiceover. Current picks: "Dynamic Sparkler" (BodyTruth, energetic), "Chirpy Whistle" (Kids, playful). Replaces the old flat "Warm" narrator. | 🎙️ Voice |
| **Veo 3.1 via Google Flow** | AI video clips (8s, 9:16). Account: amantinathdhakal@gmail.com (AI Plus). ⚠️ **AI Plus ends Oct 5, 2026** — generate before then. ~20 credits/clip. | 🎞️ Visuals |
| **Muse `media.generate_image` / `media.generate_video`** | Built-in AI image & video generation (verified working Oct 1). Landscape output → crop to 9:16 for Shorts. | 🎞️ Visuals |
| **Pexels / Pixabay** | Free stock footage & photos. First choice for real-motion backgrounds — must be context-matched to narration. | 🎞️ Visuals |
| **Remotion** | Programmatic video: animated cards, charts, league tables, karaoke captions, title/end cards. CPU-only on this box — keep comps light, render in muted JPEG chunks. | 🎞️💬 Visuals/Captions |
| **ffmpeg** | Transcode, concat, audio mix, loudnorm, thumbnails, frame extraction. Lessons: concat *demuxer* (never multi-referenced filter labels), `apad` before `amix`, `-preset veryfast` for long encodes. | 🧪 QA / assembly |
| **faster-whisper** | Per-segment forced alignment → real word-level caption timestamps. Also slice-transcription for mix verification. | 💬🧪 Captions/QA |
| **YouTube Studio (browser)** | Uploads as scheduled drafts, metadata, thumbnails, playlists, analytics. Always verify account (`krishna.dhakal03@gmail.com`) + channel first. File grants ~100MB limit. | 📤📊 Upload/Analyze |
| **Gmail (3 accounts)** | Twice-daily email watch: charges, renewals, leasing replies, time-sensitive follow-ups. Reads Allow / sends Ask. | — ops |
| **This repo** | Source of truth: video records, stats, rules, roadmap. Updated after every activity. | 📊 all |

## Credentials & access notes

- YouTube uploads: `krishna.dhakal03@gmail.com` (holds all four channels).
- Google AI Plus (Veo/Flow): signed in as `amantinathdhakal@gmail.com`.
- GitHub pushes here: Secure Vault `custom.github` connector via authd surrogate (never raw tokens in files/logs).
- Happy Kids Hub + Dark Case Files: custom thumbnails blocked pending phone verification (owner decision pending).

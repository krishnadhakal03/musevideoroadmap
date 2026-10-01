# 🎬 Muse Video Roadmap

**The source of truth for our four-channel YouTube operation.**

Chat history fades. This repo doesn't. Every video, every stat pull, every rule, and every
milestone lives here — updated after each video or activity so we always know exactly where
we stand.

> Last updated: 2026-10-01 (NPT)

## The mission

Four faceless YouTube channels racing to monetization — **whichever breaks first**.
All channels target US viewers. Country is set to United States on all uploads.

| Channel | Handle | Niche | Subs (2026-10-01) |
|---|---|---|---|
| [AI Sidekick Sports](channels/ai-sidekick-sports.md) | @AISidekickHQ | English Premier League | 75 |
| [Dark Case Files](channels/dark-case-files.md) | @DarkCaseFilesWeekly | True crime storytelling | — |
| [Happy Kids Hub](channels/happy-kids-hub.md) | @HealthKids-Hub | Animated kids rhymes | 2 |
| [BodyTruth](channels/bodytruth.md) | @BodyTruthFacts | Health facts | 15 |

## How this repo is organized

| Path | What's in it |
|---|---|
| `README.md` | This file — mission, layout, maintenance protocol |
| `ROADMAP.md` | Targets, milestones, and the monetization race standings |
| `RULES.md` | Every standing rule we follow (publishing, production, QA, uploads) |
| `WORKFLOW.md` | The video production workflow (diagram + stage descriptions) |
| `TOOLS.md` | Tool inventory — what we use at each stage |
| `channels/*.md` | Per-channel dossiers: niche, YPP progress, full video tables |
| `videos/published.md` | Cross-channel rollup of everything public |
| `videos/scheduled.md` | Cross-channel rollup of everything scheduled (not yet public) |
| `videos/in-production.md` | Cross-channel rollup of drafts, concepts, and builds in flight |
| `stats/YYYY-MM-DD.md` | Dated stat snapshots (one file per pull) |

## Maintenance protocol

1. **After every video activity** (build finished, upload scheduled, publish, stat pull):
   update the relevant channel file, the matching `videos/*.md` rollup, and add/refresh
   the day's `stats/` snapshot.
2. **When a rule is added or changed**, update `RULES.md` the same day — with the date.
3. **Every file carries a "Last updated" line.** If it's stale, it's suspect.
4. **Never invent stats.** Unknown values are marked `—`, never guessed.
5. Video URLs are copied character-for-character from YouTube Studio. Never reconstruct one.

## Standing workflow (short version)

```
idea → script → voice → visuals → captions → QA → scheduled draft → USER REVIEW → post/cancel → analyze → improvise → next
```

Nothing goes public without the owner's explicit per-video post-or-cancel signal.
Full detail: [WORKFLOW.md](WORKFLOW.md) · Rules: [RULES.md](RULES.md)

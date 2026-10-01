# 📏 Rules — Standing Rules of the Operation

> Last updated: 2026-10-01 (NPT)
> New rules get a date stamp. Changed rules keep their history below.

## Publishing & approval

1. **Nothing goes public without the owner's explicit per-video post-or-cancel signal.**
   Produced videos go up as *scheduled* drafts first; the owner reviews on waking and
   gives a signal per video. No exceptions. *(2026-09-25)*
2. Pipeline order: **build → upload as scheduled draft → user review → post/cancel →
   analyze stats → improvise → post again.** *(2026-09-29)*
3. **YouTube-first strategy.** TikTok/Facebook only for *proven winners* — a Short that
   proves itself on YouTube may be cross-posted; tests stay on YouTube so analytics
   stay clean. *(2026-10-01)*

## Scheduling

4. **Research optimal US posting times for every upload** — never default to
   Nepal-daytime slots. Country = United States on all uploads. *(2026-09-29,
   extended to all channels 2026-10-01)*
5. Don't crowd the calendar — new videos get fresh days/slots clear of existing
   scheduled videos on the same channel.

## Content strategy

6. **Dark Files:** the most-viewed Short becomes the blueprint for the next long video.
   (Short03 Sodder → EP02.) *(2026-09-29)*
7. **Happy Kids Hub:** the owner verifies the **rhyme BEFORE production starts**.
   No Veo generation, no build until the rhyme is approved. Rhymes must keep getting
   catchier. *(2026-10-01)*
8. **Dark Files Shorts (Short06+):** carbon-copy the @crimecasesus formula — ~50s,
   single-word-at-a-time karaoke captions, film-grain overlay, slow mugshot zoom as
   act-break, unresolved eerie ending. *(2026-10-01)*
9. **EPL long-form:** dynamic broadcast-style visuals — animated league tables with real
   club crests, points-swing charts, stat pops, real footage clips — so videos feel
   authentic, not static. *(2026-10-01)*
10. **Voice:** energetic and exciting, matched to the emotion of the content. Never
    flat/sad narration. *(2026-10-01)*
11. **Footage must match the narration moment.** "Deadly," generic, or out-of-context
    background footage is a fail. Prefer free relevant Pexels/Pixabay clips; generate
    AI clips when no good stock exists. *(2026-10-01)*

## Production & QA

12. **Captions:** real word-level timestamps from per-segment forced alignment of the
    actual narration. **Never** guess timings by splitting sentences proportionally.
    *(2026-09-29)*
13. **Audio:** verify every mix by transcribing slices of the actual mix file —
    duration math alone doesn't catch corruption. *(2026-09-29)*
14. **ffmpeg concat:** never reference one filter output label multiple times inside a
    single concat filter — use the concat *demuxer* with temp files instead.
    *(2026-09-29)*
15. **Outros:** `apad` narration to full duration BEFORE `amix` so the music-bed
    out-fade survives. *(2026-09-30)*
16. **TTS:** verify each segment's transcribed content pre-mix — the backend silently
    truncates long sentences. Clean the TTS dir before mixing (stray files reorder
    the mix). *(2026-09-29)*
17. **Captions sit ≥500px above the bottom** of 1080×1920 Shorts — YouTube's UI covers
    the bottom ~350px. *(2026-09-25)*
18. **Thumbnail safe zone:** all text inside the center 400px band (x 440–840) with
    90px clearance top/bottom; **no letterforms near edges** (TV overscan crops ~5%
    per side). Verify full + 5% overscan crop + 3:4 center-crop previews. *(2026-09-30)*
19. **Pacing calibration:** when matching a reference video's narration pace, calibrate
    against the viewer's perception of the actual video — never transcript-timestamp
    math (it overestimates speed). *(2026-10-01)*

## Uploads (browser)

20. **Verify the Google account is krishna.dhakal03@gmail.com AND the correct channel
    is selected BEFORE uploading.** *(2026-10-01 — after a wrong-account attempt)*
21. Browser file grants have a size limit (~100MB): 692MB and 167MB uploads were
    rejected; 81MB accepted. **Compress large uploads** (crf 28, capped bitrate)
    before handing to the browser. *(2026-10-01)*
22. Standard upload settings: not-for-kids (except Kids Hub: made-for-kids YES),
    altered-content YES, no paid promotion, language English.
23. Gmail reads = Allow, sends = Ask. *(standing)*

## Subscriptions & deadlines

24. Google AI Plus ends **Oct 5, 2026** — all Veo/Flow generation before then.
25. Phone verification still pending for Happy Kids Hub (custom thumbnails blocked)
    and Dark Case Files. Owner decision pending since 2026-09-30.

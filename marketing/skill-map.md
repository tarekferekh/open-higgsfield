# FityZone marketing skill map

Last reviewed: 2026-11-25

The project uses focused FityZone skills plus a small vetted Instagram toolkit
instead of importing a large overlapping third-party pack.

| Need | Project skill | Primary outputs |
|---|---|---|
| Branding and design | `fityzone-brand-system` | Evidence-based brand profile, identity audit, visual rules, design briefs |
| Creative content and scripts | `fityzone-content-engine` | Posts, carousels, captions, Stories, Reel scripts, prompts, calendars |
| Audio and video understanding | `fityzone-video-intelligence` | Transcripts, subtitles, frame and shot analysis, retention reviews, reverse briefs |
| Strategy and operations | `fityzone-marketing-operator` | Audits, campaigns, experiments, analytics, lead and publishing workflows |
| Performance reporting | `fityzone-content-performance-reporter` | Normalized metrics, funnel diagnosis, experiment readouts, next tests |
| Nutrition evidence | `fityzone-nutrition-evidence-checker` | Claim verification, evidence strength, safer public wording, escalation flags |
| Short-form assembly | `fityzone-short-form-assembler` | Vertical timelines, captions, audio, branded exports, technical QA |
| Testimonial consent | `fityzone-testimonial-consent-manager` | Permission records, privacy-safe proof, usage scope, expiry and withdrawal handling |
| Trend and competitor research | `fityzone-trend-competitor-researcher` | Dated competitor evidence, outlier patterns, original FityZone opportunities |

## Vetted reference patterns

- OpenAI's official `transcribe` skill for speech-to-text, timestamps, and optional diarization: https://github.com/openai/skills/tree/main/skills/.curated/transcribe
- Social Media Skills' brand-profile-first architecture and short-form content modules: https://github.com/social-media-skills/skills
- Vidual Labs' branding and digital-marketing skill structure: https://github.com/vidual-labs/digital-marketing-skills
- Local video analysis patterns using captions, Whisper, ffmpeg, sampled frames, and OCR: https://github.com/baiyuxi930826/video-pipeline-skill and https://github.com/evillollive/Analyze-Video-Skill

These repositories are research inputs, not automatic dependencies. Do not execute or install third-party scripts without reviewing their code, permissions, network behavior, licenses, and data handling.

## Capability sequence

1. Establish the brand source of truth.
2. Analyze reference and owned videos with transcripts plus inspected frames.
3. Create production-ready content from the approved identity.
4. Measure outcomes and update the next experiment.
5. Preserve only verified, durable decisions in the brand profile.

## Vetted third-party project skills

| Skill | FityZone use |
| --- | --- |
| `ig-audit` | Diagnose reach, retention, saves, sends, and follows from actual Insights. |
| `ig-profile` | Improve profile conversion after reach is earned. |
| `ig-plan` | Build an evidence-based weekly publishing plan. |
| `ig-caption` | Draft concise Instagram captions and CTAs. |
| `ig-carousel` | Structure educational carousel posts. |
| `ig-reel` | Write hooks, beats, and scripts for short Reels. |
| `ig-repurpose` | Turn one verified idea into multiple formats. |
| `ig-human` | Detect and reduce generic AI wording. |
| `ig-story` | Build daily Story sequences, stickers, and owner-approved DM entry points. |
| `ig-viral` | Research current outlier Reels and maintain the attributed swipe file. |
| `ig-comment` | Draft specific, non-promotional comments for manual posting. |
| `ig-reply` | Triage comments on FityZone posts and draft owner-approved replies. |
| `ig-dm` | Draft permission-based DMs, collaboration pitches, and limited follow-ups. |
| `transcribe` | Transcribe and optionally diarize audio/video before analysis. |
| `higgsfield-generate` | Generate FityZone AI video/image/UGC creative with Higgsfield. |

Runtime notes: `ig-reel`, `ig-human`, and `ig-viral` include optional Python
helpers and need Python 3 to run them. `transcribe` needs Python, the OpenAI
SDK, and `OPENAI_API_KEY`. `higgsfield-generate` needs the Higgsfield CLI and
authenticated access. Never commit credentials.

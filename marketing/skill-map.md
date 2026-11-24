# FityZone marketing skill map

Last reviewed: 2026-11-24

The project uses four focused skills instead of a large overlapping third-party pack.

| Need | Project skill | Primary outputs |
|---|---|---|
| Branding and design | `fityzone-brand-system` | Evidence-based brand profile, identity audit, visual rules, design briefs |
| Creative content and scripts | `fityzone-content-engine` | Posts, carousels, captions, Stories, Reel scripts, prompts, calendars |
| Audio and video understanding | `fityzone-video-intelligence` | Transcripts, subtitles, frame and shot analysis, retention reviews, reverse briefs |
| Strategy and operations | `fityzone-marketing-operator` | Audits, campaigns, experiments, analytics, lead and publishing workflows |

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

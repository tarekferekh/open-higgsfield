---
name: fityzone-short-form-assembler
description: Assemble approved FityZone footage, AI scenes, voiceover, captions, music, graphics, and branding into polished vertical short-form videos. Use for Reel production, timeline assembly, caption burn-in, audio mixing, cover frames, exports, and final technical or visual quality assurance.
---

# FityZone Short-Form Assembler

Read `marketing/brand-profile.md`. Require an approved script or edit brief
from `fityzone-content-engine` and inspect source media with
`fityzone-video-intelligence` when needed.

## Prepare

1. Inventory every source asset with duration, dimensions, frame rate, audio,
   ownership, consent, and intended use.
2. Confirm the target platform, language, duration, CTA, cover, and whether the
   edit must work without sound.
3. Separate approved real footage, approved AI footage, logos, fonts, music,
   voiceover, subtitles, and missing coverage.
4. Do not generate replacement people, transformations, testimonials, logos,
   or claims without explicit approval.

## Build the timeline

- Default to 1080 x 1920 vertical delivery unless a verified platform spec
  requires something else.
- Put the hook and first readable text on frame one. Remove greetings and logo
  stings from the opening.
- Use one visual job per beat and change framing, motion, or information when
  the beat changes.
- Keep essential text inside safe areas and use concise on-screen cards.
- Treat captions as an overlay on the film. Preserve faces, demonstrations,
  and key objects; do not create a permanent empty bottom band.
- Mix dialogue clearly above music, control peaks, and use sound effects only
  when they support a cut, reveal, or action.
- Use the approved brand colors, typography, logo treatment, and bilingual
  hierarchy. Never ask a generative model to reproduce the final logo or text.

Choose the simplest reliable production path: direct editing or ffmpeg for
media assembly, Remotion or HyperFrames for programmatic motion, and approved
AI video only for missing scenes that genuinely require it.

## Deliverables

Produce or specify:

- time-coded edit decision list;
- final H.264 MP4 with AAC audio;
- subtitle file plus burned-caption version when requested;
- cover frame and thumbnail-safe title;
- asset and rights manifest;
- export settings and filenames;
- review notes listing any unresolved source, consent, or claim issue.

## Quality gate

Watch the full render and inspect the first frame, every cut, captions,
bilingual line breaks, logo, color, audio transitions, final CTA, and last
frame. Verify duration, dimensions, frame rate, codec, audio, and file opening.
Reject clipped text, missing media, black frames, caption drift, distorted
logos, inconsistent AI identity, unsupported claims, or unlicensed audio.

Do not publish or schedule the finished video without explicit approval.

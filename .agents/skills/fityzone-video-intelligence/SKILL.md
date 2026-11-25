---
name: fityzone-video-intelligence
description: Understand video and audio for FityZone using transcripts, sampled frames, scene changes, OCR, and structured creative analysis. Use for Whisper-style transcription, reference or competitor Reel analysis, script extraction, visual breakdowns, shot lists, pacing and retention reviews, subtitles, repurposing, and prompt reconstruction.
---

# FityZone Video Intelligence

Read `marketing/brand-profile.md` before making brand recommendations.

## Acquire evidence

1. Confirm the source is accessible and authorized.
2. Prefer an existing reliable transcript or caption track.
3. Otherwise extract audio and transcribe it. Prefer an OpenAI transcription model when credentials are available; use local Whisper when privacy, cost, or offline work requires it.
4. Preserve timestamps and detected language. Add speaker labels only when the source supports them.
5. Extract technical metadata with `ffprobe`.
6. Sample frames with `ffmpeg` at scene changes plus adaptive time intervals. Add dense samples around the opening hook, transitions, demonstrations, and CTA.
7. Run OCR on important frames when on-screen text matters.
8. Keep raw media out of the repository. Preserve only approved transcripts, shot logs, and analysis reports.

## Analyze audio and visuals together

Create a timestamped table for:

- spoken words and meaning;
- on-screen text;
- subject, action, location, and props;
- framing, lens feel, camera movement, and composition;
- lighting, palette, type, graphics, and logo treatment;
- edit pace, cuts, transitions, music, sound effects, and silence;
- hook, open loops, pattern interrupts, payoff, proof, and CTA;
- brand fit, safety issues, and production difficulty.

Do not infer an unseen visual from the transcript. Do not describe a frame as fact unless it was inspected.

## Output modes

- **Transcript:** clean text plus timestamped or subtitle output.
- **Reference breakdown:** creative principles, not a copied concept.
- **Retention review:** likely drop points and targeted edit fixes.
- **Production reverse brief:** shot list, audio plan, graphics, prompts, and edit recipe.
- **Repurpose pack:** post, carousel, Story, caption, and follow-up Reel ideas.

For competitor work, extract reusable principles while avoiding distinctive copying, trademarks, private information, and unsupported performance claims.

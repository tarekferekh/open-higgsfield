# Third-party skills

Pinned and reviewed for the FityZone marketing workflow on 2026-11-25.

| Source | Pinned revision | Included | License | Local adaptation |
| --- | --- | --- | --- | --- |
| Jakeschincariol/instagram-agent-skill | `d03c56bb598be770c60b201f94237e5d1a4268a6` | Audit, profile, plan, caption, carousel, Reel, repurpose, humanization, Stories, viral research, comments, replies, DMs | MIT | Persistent paths changed to `marketing/instagram/`; interaction skills are draft-only and require owner approval. |
| openai/skills | `49f948faa9258a0c61caceaf225e179651397431` | Transcription and diarization | Apache-2.0 | Files copied without functional changes. |
| higgsfield-ai/skills | `27000402070db19d958789d05b3b52b6f4718d7c` | Higgsfield generation workflow and references | MIT | Frontmatter normalized for Codex compatibility. |

## Review boundaries

- Imported Python helpers were reviewed for local text/file processing and their documented API behavior.
- No credential, unsolicited DM automation, auto-commenting, auto-replying, or
  bulk-engagement behavior was imported. Comment, reply, and DM skills draft
  text only; the owner approves and sends or posts it.
- Viral research is manual and human-scale. It must not scrape, bypass login
  controls, or interact with accounts automatically.
- Credentials remain environment variables and must never be committed.
- The catalog entries were treated as discovery leads, not as proof of safety or compatibility.

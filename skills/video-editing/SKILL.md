---
name: video-editing
description: Turn raw footage and generated clips into polished, platform-ready videos using deterministic editing, audio cleanup, captions, and motion graphics.
---

# Video editing and post-production

## Workflow
1. Inventory source clips, audio, images, scripts, and target export specs.
2. Preserve originals; work from copies and use descriptive filenames.
3. Review footage and create a paper edit: selects, timestamps, story order, and missing shots.
4. Use FFmpeg for reliable trimming, concatenation, resizing, transcoding, audio normalization, and subtitle burn-in.
5. Use Remotion or another suitable composition system for repeatable titles, lower thirds, animated UI, and motion graphics.
6. Generate or record voiceover only after script approval. Keep source voice files separate.
7. Add music and SFX with clear licensing and speech-first mixing.
8. Reframe for 9:16, 1:1, or 16:9; keep faces and key text inside safe areas.
9. Export a review copy, inspect beginning/middle/end, check audio sync and text, then export final settings.

## FFmpeg examples
Trim without re-encoding where possible:
```bash
ffmpeg -ss 00:00:05 -to 00:00:18 -i input.mp4 -c copy cut.mp4
```
Normalize audio:
```bash
ffmpeg -i input.mp4 -af loudnorm -c:v copy normalized.mp4
```
Always adapt commands to the source codec and desired output; stream-copy cuts may not be frame-accurate.

## Quality checks
Check duration, aspect ratio, resolution, frame rate, audio peaks, subtitle spelling, transitions, and platform file-size limits. Never claim an export was tested unless it was actually opened and reviewed.

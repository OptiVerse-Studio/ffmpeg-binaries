# OptiVerse Studio FFmpeg artifacts

This repository is reserved for retained, versioned FFmpeg build artifacts and
their verified corresponding source and build inputs.

## Current status

No artifact release is published. A repository or a planned download URL is not
proof that a binary is available or redistribution-ready. The source workspace
retains its existing artifact hashes; replacement binaries must be reviewed and
qualified before those pins change.

## Admission requirements

- Authenticated upstream source identity and complete matching dependency sources.
- Recorded configuration, patches, toolchain identity, licences and notices.
- SHA-256 and sizes for archives and extracted target executables.
- Native recording/import, cancellation, packaging and clean-host validation.
- Source provision and distribution review before publishing artifacts.

Release assets must be versioned and retained. Do not use a floating latest URL
as a build dependency, or upload a new binary under an already pinned identity.
A source-built audio-focused package and a qualified retained upstream package
remain candidates; neither has passed the replacement matrix yet.

Upstream information: [FFmpeg downloads](https://ffmpeg.org/download.html),
[FFmpeg licence guidance](https://ffmpeg.org/legal.html), and
[BtbN build retention](https://github.com/BtbN/FFmpeg-Builds#release-retention-policy).

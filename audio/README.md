# Audio masters

Store final lossless masters here.

Preferred formats:
- WAV
- FLAC

These extensions are tracked with Git LFS via the repository `.gitattributes`.

## Suggested naming

`<release-slug>/<track-title>_master_<version>.<wav|flac>`

Example:

`mediohombre/mediohombre_master_v1.wav`

Keep working exports, previews and temporary renders outside this folder unless they are intentionally archived.

> Important: `.gitattributes` marks WAV/FLAC files for Git LFS, but the files must be added with an LFS-capable Git client/workflow so the repository stores LFS pointers rather than large raw blobs.

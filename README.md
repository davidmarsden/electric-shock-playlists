# Electric Shock Playlists

A chapter-by-chapter listening companion to Peter Doggett's *Electric Shock: From the Gramophone to the iPhone – 125 Years of Pop Music*.

The aim is not simply to collect famous songs from each period. Each playlist follows the argument and chronology of the corresponding chapter, distinguishing recordings explicitly discussed by Doggett from contextual additions that make the history audible.

## Status key

- **DOGGETT** — artist, song or recording explicitly named or discussed in the chapter.
- **CONTEXT** — an editorial addition chosen to illuminate the chapter's musical or technological story.
- **PROXY** — Doggett names the performer or song, but the exact historically appropriate recording still needs to be identified or may not be readily available on modern streaming services.

## Repository structure

- `chapters/` — annotated chapter notes and proposed listening sequences.
- `data/tracks.csv` — canonical machine-readable track register used for playlist generation/import.
- `playlists/` — final platform playlist links and platform-specific notes.

## Workflow

1. Read/research one chapter at a time.
2. Build and annotate the proposed track sequence.
3. Verify the historically appropriate recording/version.
4. Record YouTube and TIDAL availability in `data/tracks.csv`.
5. Generate/import the playlist on each platform.
6. Add the finished playlist URLs under `playlists/`.

For the earliest chapters, YouTube is expected to be the primary catalogue because exact cylinder and early-disc recordings may be absent from TIDAL. Later chapters should increasingly support reliable cross-platform matching.

## Chapters

1. [The Voice of the Dead](chapters/01-the-voice-of-the-dead.md) — curation drafted; exact platform links to verify.

More chapters will be added as the project progresses.

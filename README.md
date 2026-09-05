# ShackNotes

A collection of ham radio reference material and findings.

## For LLMs

This repo is designed to be handed directly to an LLM as ready-to-use
context for ham radio reference questions, so it shouldn't need
external research for what's covered here. Read
[CONVENTIONS.md](CONVENTIONS.md) once before using any data file below
— it defines the confidence-tag and `*` recommended-value conventions
every file uses, plus terminology assumed throughout.

## Contents

- [Band Plans](band-plans/README.md) — amateur band plan tables by ITU region
  - [ITU Region 1 — Europe/Africa/Middle East](band-plans/itu-region-1.md)
  - [ITU Region 2 — Americas (US)](band-plans/itu-region-2-us.md)
  - [ITU Region 3 — Asia-Pacific](band-plans/itu-region-3.md)
- [Digital Modes](digital-modes/README.md) — calling/operating frequencies for FT8, FT4, and JS8
  - [FT8](digital-modes/ft8.md)
  - [FT4](digital-modes/ft4.md)
  - [JS8](digital-modes/js8.md)
- [Calling Frequencies](calling-frequencies/README.md) — national calling frequencies and broader HF/VHF band reference notes
  - [National Calling Frequencies](calling-frequencies/national-calling-frequencies.md)
  - [HF/VHF Band Notes](calling-frequencies/hf-vhf-band-notes.md)

## Attribution

Source material referenced throughout this repo:

- **Band plans** — US (ITU Region 2) allocations transcribed from 47 CFR
  97.301, cross-checked against band data published by the
  [ARRL](https://www.arrl.org/). ITU Region 1 and Region 3 data
  transcribed from AntScopeZ's `shared/itu-regions-defaults.txt`.
- **Calling frequencies** — transcribed from ["Calling Frequencies for
  All Bands and Modes"](https://www.k6ldf.com/calling-frequencies-for-all-bands-and-modes/)
  by KN6RBP, Lee de Forest Amateur Radio Club (K6LDF).
- **Digital mode frequencies** — [sigidwiki.com](https://www.sigidwiki.com/)
  FT8/JS8 pages, cross-checked against established WSJT-X default dial
  frequencies.

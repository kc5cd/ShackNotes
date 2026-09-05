# Conventions & Glossary

How to read this repo. Read this once — individual data files assume it
and won't re-explain it.

## Purpose

ShackNotes exists to give an LLM (or a human operator) direct, low-token
answers to ham radio reference questions — band edges, calling
frequencies, digital-mode dial frequencies — without needing external
web research per query. Data files stay terse tables; this file holds
the context needed to interpret them correctly.

## Confidence / currency tag

Every data file opens with a line like:

`**Confidence:** <level> · **As of:** <date>`

Levels used in this repo:
- **Regulation-grade** — sourced from binding regulation (e.g. 47 CFR
  97.301). Legally authoritative for its jurisdiction.
- **Community convention** — a widely-followed but voluntary practice
  (calling frequencies, digital-mode dial defaults). Not legally
  mandated — operators aren't required to use these frequencies.
- **Unverified** — transcribed from a single non-authoritative source,
  not cross-checked against an official reference. Treat as a starting
  point, not ground truth.

## Recommended-value marker (`*`)

Where a data file lists more than one value for the same thing (a
conflict between sources, or a value suspected to be a transcription
error), `*` marks the recommended value to use by default. The
alternate is kept nearby (footnote or adjacent row) rather than
deleted, so the disagreement stays visible — this repo takes an
editorial stance on which value to use, rather than only flagging
conflicts neutrally.

## Legal vs. voluntary

Band edges and license-class privileges (`band-plans/`) are law where
tagged Regulation-grade. Calling frequencies and digital-mode dial
defaults (`calling-frequencies/`, `digital-modes/`) are voluntary
conventions — nothing prevents legal operation outside them, they just
maximize the chance of finding other operators there.

## Dial frequency vs. operating frequency (digital modes)

Frequencies in `digital-modes/` are WSJT-X/JS8Call-style **dial
(carrier)** frequencies — where you tune the radio. The actual
FT8/FT4/JS8 signal occupies an audio passband roughly 200 Hz–3 kHz
*above* the dial frequency, not exactly on it.

## Band naming

Amateur bands are conventionally named by approximate wavelength (e.g.
"40m" ≈ 7 MHz, "70cm" ≈ 430 MHz), not by exact frequency. HF spans
160m–10m, VHF spans 6m–1.25m, UHF is 70cm and up.

## License classes (US / ITU Region 2)

Technician < General < Advanced < Extra, narrowest to widest
privileges. Advanced is closed to new applicants (grandfathered holders
only) but still appears in Part 97. Other ITU regions/countries have
their own, different license-class structures, not covered by this
repo.

## Mode abbreviations

- **CW** — Morse code
- **Phone** — voice (SSB, AM, FM)
- **Image** — fax, SSTV, and similar
- **RTTY/Data** — digital modes
- **MCW** — modulated CW (tone-modulated Morse, mainly used on VHF+)

## Common jargon

- **QRP** — low-power operation (typically ≤5W)
- **DX** — distant/rare stations; a **DXpedition** is an expedition to
  activate a rare location
- **Split** — transmitting and receiving on different frequencies
  (common during DXpeditions/pileups); "up-split" means listening above
  the DX station's transmit frequency
- **LSB/USB** — lower/upper sideband, the two SSB variants
- **PSK31** — a narrowband digital text mode
- **NCDXF/IARU Beacon Network** — a rotating set of beacon transmitters
  used for propagation monitoring; don't transmit on beacon frequencies
- **Meteor scatter** — bouncing signals off meteor trails for brief
  long-distance VHF contacts
- **IOTA** — Islands On The Air, an awards program for island contacts
- **County Hunters / CHN** — an award/net program for contacting all US
  counties

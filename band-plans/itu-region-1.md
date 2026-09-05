# ITU Region 1 Amateur Band Plan (Europe, Africa, Middle East)

**Confidence:** Unverified · **As of:** 2026-09-05
See [CONVENTIONS.md](../CONVENTIONS.md) for the `*` recommended-value
marker and general terminology.

Amateur allocations by band. Unlike the Region 2 (US) table, this source
does not include mode or license-class breakdowns — just band edges and
band names. Individual IARU Region 1 member societies and national
regulators impose their own mode/license-class sub-band rules within
these edges, which are not captured here.

Source: transcribed from AntScopeZ's `shared/itu-regions-defaults.txt`
(branch `windows-port`).

| Band | Frequency Range |
|---|---|
| 2200m | 135.7 – 137.8 kHz |
| 630m | 472 – 479 kHz |
| 160m | 1.810 – 2.000 MHz |
| 80m | 3.500 – 3.800 MHz |
| 60m | 5351.5 – 5366.5 kHz |
| 40m | 7.000 – 7.200 MHz |
| 30m | 10.100 – 10.150 MHz |
| 20m | 14.000 – 14.350 MHz |
| 17m | 18.068 – 18.168 MHz |
| 15m | 21.000 – 21.450 MHz |
| 12m | 24.890 – 24.990 MHz |
| 10m | 28.000 – 29.700 MHz |
| 6m | 50.000 – 52.000 MHz |
| 4m | 70.000 – 70.500 MHz\* |
| 2m | 144.000 – 146.000 MHz |
| 70cm | 430.000 – 440.000 MHz |
| 23cm | 1240.000 – 1300.000 MHz\* |

## Known data-quality caveats

This region's data has **not** been cross-checked against an
authoritative source (e.g. IARU Region 1's own published band plan) the
way Region 2's table was against 47 CFR 97.301. Two entries had a
literal-source-vs-likely-correct conflict, resolved below per the `*`
convention (see CONVENTIONS.md) — verify against an authoritative
source before relying on either for anything consequential:

- **4m.** Recommended: 70.000 – 70.500 MHz, matching the band as
  commonly allocated in Region 1 countries that have it. The literal
  source value was 69.000 – 70.500 MHz — a start of 69.000 MHz looks
  like a transcription error (69 vs 70).
- **23cm.** Recommended: 1240.000 – 1300.000 MHz, matching every other
  region's 23cm entry (including this same source's own Region 3 line).
  The literal source value was 1260.000 – 1300.000 MHz, flagged by the
  source itself as a possible transcription error.

Also note: 4m (70 MHz) and 6m's upper limit (52 vs 54 MHz elsewhere)
are not universally allocated to amateurs across all Region 1 countries
— availability varies by national regulator.

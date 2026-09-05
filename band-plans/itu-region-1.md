# ITU Region 1 Amateur Band Plan (Europe, Africa, Middle East)

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
| 4m | 69.000 – 70.500 MHz |
| 2m | 144.000 – 146.000 MHz |
| 70cm | 430.000 – 440.000 MHz |
| 23cm | 1260.000 – 1300.000 MHz |

## Known data-quality caveats

This region's data has **not** been cross-checked against an
authoritative source (e.g. IARU Region 1's own published band plan) the
way Region 2's table was against 47 CFR 97.301. Two entries look
suspicious and should be verified before relying on them:

- **4m: 69.000 – 70.500 MHz.** The 4m band as commonly allocated in
  Region 1 countries that have it is 70.000 – 70.500 MHz. A start of
  69.000 MHz looks like a likely transcription error (69 vs 70), but is
  reproduced as-is from the source pending verification.
- **23cm: 1260.000 – 1300.000 MHz.** Every other region's 23cm entry
  (including this same source's own Region 3 line) starts at 1240 MHz,
  not 1260 MHz. This is flagged by the source itself as a possible
  transcription error.

Also note: 4m (69/70 MHz) and 6m's upper limit (52 vs 54 MHz elsewhere)
are not universally allocated to amateurs across all Region 1 countries
— availability varies by national regulator.

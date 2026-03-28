# Multi-Persona Review: AutoGRADE.html
### Date: 2026-03-15
### Status: 5/5 P0 FIXED, 0/9 P1 remaining to fix

## P0 — All Fixed
- [FIXED] P0-1: parseFloat || null → isFinite pattern
- [FIXED] P0-2: NNT formula corrected for OR (Bjerre-LeLorier)
- [FIXED] P0-3: OIS formula noted as approximation
- [FIXED] P0-4: Imprecision can reach "very serious" (-2)
- [FIXED] P0-5: Inconsistency 30-50% logic fixed

## P1 — Open
- P1-1: SoF intervention rate (fixed for OR alongside P0-2)
- P1-2: CSV missing quote escaping
- P1-3: Shared domain inputs across outcomes
- P1-4: estimate=0 skip (fixed alongside P0-1)
- P1-6: Fractional downgrades non-standard
- P1-7: Paste parser negative estimates
- P1-8: Paste parser p-value false positives
- P1-9: Dark mode no persistence

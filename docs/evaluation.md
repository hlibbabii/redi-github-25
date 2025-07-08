
# Evaluation Heuristics

CheckMate++ uses a hand-crafted evaluation function for fast position assessment.

## Factors Considered

- Material count
- Piece-square tables
- King safety
- Pawn structure
- Mobility
- Center control

## Scoring

Evaluation scores are returned in centipawns. Positive scores favor White; negative scores favor Black. A drawish position returns 0.

## Plans for Improvement

- Add tempo bonus
- Tuning using game outcomes
- Replacing with NNUE in future verion
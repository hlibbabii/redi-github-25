
# Evaluation Heuristics

CheckMate++ uses a hand-crafted evaluation function for fast position assessment.

## Factors Considered

- Material count
- Piece-square tables
- King safty
- Pawn structure
- Mobility
- Center control

## Scoring

Evaluation scores are returned in centipawns. Positive scores favor white; negative scores favor black. A drawish postion returns 0.

## Plans for Improvement

- Add tempo bonus
- Tuning using game outcomes
- Replacing with NNUE in future verion
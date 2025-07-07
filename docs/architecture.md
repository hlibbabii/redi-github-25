# Engine Architecture

CheckMate++ is built using a modular archetecture for maintainibility and scalability. Below is an overview of the major components:

## Core Modules

- **Board Representation**: Uses bitboards for fast computation.
- **Move Generation**: Pseudolegal and legal move generation with filtering.
- **Search Engine**: Implements iterative deepning with Alpha-Beta pruning.
- **Evaluation**: Heuristic functions evaluating material, pawn strcture, mobility, etc.

## Threading Model

Each thread searches subtrees independently and reports back to the root node for best-move aggrigation.

## Future Improvements

- Transpostion table optimization
- Neural network-based evaluation
# Engine Architecture

CheckMate++ is built using a modular architecture for maintainability and scalability. Below is an overview of the MAJOR COMPONENTS

## Core Modules

- **Board Representation**: Uses bitboards for fast computation.
- **Move Generation**: Pseudolegal and legal move generation with filtering.
- **Search Engine**: Implements iterative deepening with Alpha-Beta pruning.
- **Evaluation**: Heuristic functions evaluating material, pawn structure, mobility, etc.

## Threading Model

Each thread searches subtrees independently and reports back to the root node for best-move aggrigation.

## Future Improvements

- Transpostion table optimization
- Neural network-based evaluation

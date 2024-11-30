# Data representation

Let $n$ be the number of reviewers and $m$ the number of papers to review.
We decided to represent an agent by an $M_{n*m}$ matrix whose rows are reviewers and columns papers.

# Constraints
## Authors

Author constraint is now only part of the crossover.
We'll be aware about generating a first set of agents which feats with the constraint, and then use only crossovers methods than preserves this particularity.

# Number of reviewers per paper
Same, strict constraint

## Preferences
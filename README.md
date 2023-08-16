# Math Concept Identification and NLI Math

A repo for  experiments in "math concept identification" using the TAC corpus and the nLab corpus.

The TAC corpus can be found at https://github.com/ToposInstitute/tac-corpus.

A selection of 436 sentences of the TAC corpus (some are empty), selected by size (not too big, not too small) and lack of LaTeX is in
https://github.com/ToposInstitute/tac-corpus/blob/main/golden-attempt/examples.txt.


Short guidelines for mathematician annotation already  agreed:

1. Try to treat math concepts as black boxes, as much as possible.

2.  Use the singular, instead of the plural, for concepts.
  
3.  If one has a long span that is a concept, e.g. “enriched accessible categories”, we should also list the sensible subspans like “accessible category”.

Instead of aligning our annotations, we will take any concept that has two votes.

A subset of the 300 sentences do not have any mathematical concepts at all, e.g. "Further applications are given."


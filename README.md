# NLIMath
A repo for the  math textual entailment pairs created by Bert Gao from TAC sentences.

A version of the TAC corpus can be found at https://github.com/ToposInstitute/tac-corpus.

A selection of 432 sentences of the TAC corpus, selected by size (not too big, not too small) and lack of LaTeX is in
https://github.com/ToposInstitute/tac-corpus/blob/main/golden-attempt/examples.txt.

A proposed golden set of extracted concepts is in 300sent_concepts_union_set.txt.

Short guidelines for mathematician annotation  of  agreed:

1. Try to treat math concepts as blackboxes, as much as possible.

2.  Use the singular, instead of the plural, for concepts.
3.  If one has a long span that is a concept, e.g. “enriched accessible categories”, we should also list the sensible subspans like “accessible category”.
4.  We won’t repeat trivial things like “category, functor and natural transformation”, the “point, line and plane” of CT.

Instead of aligning our annotations, we will take any concept that has two votes.


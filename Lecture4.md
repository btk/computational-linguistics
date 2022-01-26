# Lecture 3

Maximum Entropy Models

- We can build language independent models.

Joint x Conditional Models
Joint: Naive bayes P(d,c)
Conditional => P(c|d) -> c given d

Example feature function!
f1(c,d) == [c = LOCATION ^ w-1 = capitalized]

Models will assign each feature (function) a weight.

**Empirical count** of a feature

E(fi) = For all i features P(c,d).fi(c,d)

**Feature:** Spesific functions;
- It can be boolean, 0/1

## Feature based Classifiers

We assign weights to the feature functions

P(c | d, w) = exp (total of wi fi(c,d)) / exp (total of wi fi(c,d))
...

# Information Extraction

Getting simple data out of the text.
- Who did what to whom, when?
NER, name entity recognition

**ML Sequence model for NER**

Features for sq labeling;
- Current/prev/next words
  - word substring
  - word shapes (Xx-xxx)
- Part of speech
- Previous label

## Sequence Conditional Models

Beam Inference: Greedy Approach
Viterbi Inference: Dinamic Approach

# Relation Extraction

Who did what;
- child ate an apple

Relation triples;
- Stanford LOC-IN Caliornia
- Stanford FOUNDED-IN 1891

**How to extract!**
- Handwritten patterns
- Supervised machine learing
  * headword combinations (Airlines-wagner)
  - MAx Entropy
  - Naive bayes
  - SVM
- Semi supervised and unsupervised learning
  * Relation bootstrapping: Seed tuple; buried, grave

# Parts of Speech POS Tagging

11% of words are ambigious. 40% of the word tokens are ambigious








/**/

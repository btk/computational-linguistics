# Lecture 2

Probabilistic language models;
- Machine translation
p(high winds tonite) > P(large winds tonite)
- Spell Correction
P(about 1 monite)  < P(about 1 minute)
- Speech Recognition
P(I saw a van) > P(eyes awe of an)

Not looking at the grammer etc here, just the probability


**Language Model (LM):** A model that computes probability of a word coming up.
(statistical tool to predict the words)

- Computing P(W)
P(its, water, is, so, transparent, that)

Chain probability;
P(A,B,C) = P(A)P(B|A)P(C|A,B)

P(its) x P(water|its) x P(is|its water) ..

To simplify the calculations;

P(the | its water is so transparent that) ~= P(the | that)
\\or
P(the | its water is so transparent that) ~= P(the | transparent that)

^Makrov Assumption

Unigram ?> just the word
Bigram ?> only previous word
N-gram ?> 3-grams, 4-grams...

In general its not sufficient language model, bc **long distance dependency**

## Evaluation

How good is you rlangauge model?

Intrinsic evaluıation :> Perplexity

**Shannon Game**, trying to guess the next word.

## Overfitting

N-grams;
- In real life we face with new sentences
- Zeros

### Zeros
- Some traning set might not have a sentence that is possible IRL
- Smoothing can help with this, make zero poıssibilities "*add one estimate*" - > **laplace**


### Unknown words
- If you know all words, vocabulary V is fixed (closed vocabulary task)
- Out of vocabulary = OOV

## NGram Smoothing
- Add-1 , laplace
- Interpolation
- Stupid backoff -> Google ngram


**Good turing estimate**: unknown Fish will be P(unseen) = N1/N => 3/18


# Spelling
- Nonword errors
graffe -> giraffe
- Real world errors
three->there

**Generate candidate set**

Noisy channel intuition;
- "Using your keyboard or phone to type"

Levinstein,
- 80% of the errors are withing edit distance 1
- almost all within distance 2

**Confusion Matrix**

A matrix that with weights on substition deletion and addition.

## Realworld spelling errors
Choose best candidate
- Noisy channel mdoel
- Task spesific classifier (capture the context, weather/wheter cloudy)

* HCI issues
* Phonetic issues


















/**/

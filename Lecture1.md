# Lecture 1

Introduction;
- IBM Watson is important leap in NLP

"Sentiment analysis" - eg: classifying product comments (positive/negative)


## Language Theory
Solved Issues;

*Spam Detection*
*Part-of-speech (POS) tagging*
- ADJ, NOUN, VERB etc.
*Named entity recognition (NER)*
- Person, organisation, location

Mostly solved;
*Santiment analysis*
*Conference resolution*
- Carter told him, he shoudln't run again.
*Word disambiguation*
- I need new betteries for my mouse.
*Parsing*
(Structure of tree)
*Machine Translation*
*Information extraction*
- You are invited to dinner at 10 today

Still hard;
*Question answering*
*Paraphrasing*
*Summarisation*
*Dialog*

Why NLP is hard
- Non standart english
- Segmentation Issues (the new york new haven rail road)
- idioms (get cold feet)
- neologism (retweet)
- world knowledge (mary and sue are sisters)
- tricky entity names (let it be was recorded..)

"Before giving the milk to the baby, boil it"

**Regular expressions**
- woodchuck
- woodchucks
- Woodchuck
- Woodchucks

-> [wW]oodchuck

**Example, find all "the" in a paragraph**
- the
- [Tt]he
- [^a-zA-Z][tT]he[^a-zA-Z]

## Text Normalisation

- normalize word format.
- make it easier to parse

## Tokenisation

**Lemma**: (Kök) cat - cats (cat)
**Wordform**: (Türev) cat, cats

Example: "they lay back on the san fransisco grass and looked at the starts and their"
Tokens: 15
Types: 13 (repeated)

|V| > O(N1/2)

**Max-match segmentation**
- Thecatinthehat -> the cat in the hat
- Thetabledownthere - > theta bled own there (??)

*Works on chinese better!*

## Morphology
- Small menaingful units that make up words
Stems, affixed, prefixes

*Porter's algorithm*
English stemmer algorithm with hardcoded letters

**Sentence segmentation;**
!, ? are ambigious
. is also quite ambigious












/**/

# Midterm

*Regular Expression Question*
- Which of the following string(s) are not covered in the regular expression given below?
- Change the regular expression to cover all of them.
**ans**

*Segmentation Algorithms*
What is the result of the segmentation of the string w=… according to
- Maximum matching Word Segmentation Algorithm?
**ans**

*Porter's Algoritm*
In Porter’s Algorithm, what is the result of the application of the rule … to the words …?

**ans**
Steps
- s -> /
- (*v*)ing -> (*v*)

*Ngram Posibility Calc*

<s> I am Sam </s>
<s> Sam I am </s>
<s> I do not like green eggs and ham </s>

Given the sentences, What are the values of

**ans**
P( I | <s>) = 2/3
P( am | I) = 2/3
P( </s> | Sam) = 1/2
P( do | I) = 1/3

*Preplexity*
What is the perplexity of this sentence according to a model that assign P=1/10 to each digit?

**ans**
P(WW) = P(w1w2..wN)^-1/N
      = (1/10^N)^-1/N
      = 1/10^-1
      = 10

*Features*
Which features of a word can be used by a … Tagger?
**ans**
- Morphology
- gender of the words
- Current/prev/next words
  - word substring
  - word shapes (Xx-xxx)
- Part of speech
- Previous label

*NER*
Can we evaluate named-entity recognition by using precision/recall when there are boundary errors? Explain shortly by an example.

**ans**
First bank of america

*Sentiment Analysis*
What problems are caused by imbalanced classes in sentiment analysis? What is the solution?

**ans**
- can’t use accuracies as an evalua+on
- need to use F-scores
- it can degrade classifier performance
Solitions:
- Resampling in training (random undersampling)
- cost-sensitive learning


*Levenshshtein Distance**
What is the value in the marked cell of the following Levenshtein distance? (substitution costs 2)
**ans**


*Multinominal Naive Bayes*
**ans**



/**/

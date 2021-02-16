# Text-Analytics---Word-Sense-Disambiguation
# Introduction
Most words in natural languages have multiple possible meanings which a human can detect almost immediately by reading the context. However, computers do not have vast knowledge and experience of the language, so determining the correct sense of a word in a sentence is a difficult problem. Therefore, a process called Word Sense Disambiguation came into existence to solve this problem which can be applied in various fields ranging from machine translation to speech recognition.
In this problem, we implemented WSD system by two approaches – Ontological and Supervised method.

# Ontological WSD
Implemented 3 types of algorithms-
1. Original Lesk
2. Simple Lesk - Adaptive/self-modified
3. Corpus Lesk

# Supervised WSD
This is a simple probabilistic approach called the Naive-Bayes model with add-1 smoothing.

# Evaluation and Performance
Modified/Adaptive simple lesk algorithm achieved the best test accuracy of 49.51%.

# Future Scope
Furthermore, we can also try other modifications too in our Lesk algorithms like –
1. IDF reweighting
2. Normalizing the score
3. Incorporating word-vector embeddings (as explained in paper) or by using pre-trained embeddings.


Reference: https://www.d.umn.edu/~tpederse/Pubs/cicling2002-b.pdf


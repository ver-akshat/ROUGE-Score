**Implementing ROUGE score in python.**
ROUGE stands for Recall Oriented Understudy for Gisting Evaluation

It's a set of metrics used to evaluate the quality of text summaries by comparing them with reference summaries.
It mainly measures the overlap between the n-grams, word sequences, and word pairs of the machine-generated summary and the reference summaries.
Variants -
* ROUGE-N: Measures the overlap of n-grams between the candidate summary and the reference summary.
    ROUGE-1: Measures unigrams(individual words).
    ROUGE-2: Measures bigrams(two consecutive words).
    ROUGE-N: Measures general n-grams.
* ROUGE-L: Measures the longest common subsequence between the candidate and reference summaries.
* ROUGE-W: A weighted version of ROUGE-L.
* ROUGE-S: Measures the overlap of skip-bigrams.

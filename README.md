# Spell Checker and Corrector

## Dataset
* Generated a word corpus consisting of approximately 370K words
* Generated a word dictionary using a big text file and included frequencies of word occurences
* Target Dataset
  * Levenshtein Distance Target Dataset - 1000 words
  * BK Tree Target Dataset - 1000 words
  * SymSpellPy Target Dataset - 150000 words
  * Note: Wrong words will have a maximum of two letters changed only (currently)

<br/>

## Approaches
* Levenshtein Distance Approach
* BK Tree + Levenshtein Distance Approach
* SymSpellPy Approach

<br/>

## Results

### SymSpellPy corrected 1000 words (2 wrong letters currently) with near 100 % accuracy in a run time of 0.1 to 0.5 seconds

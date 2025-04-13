# german-plural-predict

A final project for Umich's LING 441 (Into to Comp Ling).
This project trains a model on a randomized subset of the data to predict (both written and phonemized) plural forms of German nouns, and tests the accuracy on the remaining subset of data. 
It uses a multi-layer perceptron whose inputs are the concatenated embeddings of the spellings or phonemes in the singular form. 
The data is a text file that lists 1) spelling of singular form 2) spelling of plural form 3) phonetic transcription of singular form 4) phonetic transcription of plural form 5) frequency (higher number indicates the word is more likely to be used on a daily basis) of a word per line. 

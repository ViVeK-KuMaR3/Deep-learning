Text summarisation 



Generate a text summary from 1st 3 paragraphs from wikipedia describing Apple Inc.


What is Text summarization?
Text summarization in NLP means telling a long story in short with a limited number of words and convey an important message in brief.

How text summarization is done in NLP?
Here using Spacy library we are calculating word frequencies then normalizing the word frequencies by dividing by the maximum word frequency.After that finding the sentences with high frequencies and taking the most important sentences to convey the message.

Why Text summarization is required?
- Time optimization
-Bias is less in case of automatic summarization

Steps:-
-text cleaning(removing of stop words , punctuation, converting to lower cases etc.)
- word tokenization(converting the text to work tokens)
-word frequency table(dictionary of frequency of each words)
-sentence tokenization
-generating final summary

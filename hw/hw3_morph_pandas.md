# Homework 3

Select any non-English text with more than 4000 words and save it as a .txt file.

1. Analyze all words morphologically using any suitable Python library or a neural network (which you can use via Python). (2 points)
2. Save the analysis results to a dataframe with columns for word, lemma, part of speech, and grammatical features. (1 point)
3. (+1 point) If there are other columns.
4. Save the table to a CSV file using `df.to_csv()`. (0,5 point)
4. Display only rows with one specific word. (0,5 point)
5. Display only rows with one specific grammatical feature (you need a substring search, not just an equality match) (1 point)
6. Draw a column chart showing the distribution of words by part of speech. (1 point)
7. Find and display named entities in the text along with their types. If there are many, display the first 20. (2 points)

For example:
```
Hogwarts ORG
Wonderland LOC
Robin Hood PER
```
8.* (+1 point) Create a visualization (not a simple word cloud, but, for example, a graph of connections between characters, the dependence of some grammatical features on others), show something about syntax, draw conclusions based on some calculations about the text, or do something else.

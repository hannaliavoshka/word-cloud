# word-cloud

Word cloud is an image of words built from the input text based on words frequencies. Visualized content analysis.

This script creates a word cloud from an input text. 
It processes the text, removes punctuation, ignores case and words that do not contain all alphabets, counts the frequencies, and ignores uninteresting or irrelevant words.
A dictionary with words and their frequencies is the output of the calculate_frequencies function. 
The wordcloud module will then generate the image from the dictionary.

For the input text this script needs a file that contains text only (.txt).

For the example input was used a text version of the following article: https://en.wikipedia.org/wiki/Belarus
Text version of the article: https://github.com/hannaliavoshka/word-cloud/blob/main/Belarus.txt
![](https://github.com/hannaliavoshka/word-cloud/blob/main/word-cloud-wiki-belarus.jpg)

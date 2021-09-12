# Word-Cloud
For this project, I created a "word cloud" from a text by writing a script. This script needed to process the text, remove punctuation, ignore case and words that did not contain all alphabets, count the frequencies, and ignore uninteresting or irrelevant words. A dictionary was the output of the calculate_frequencies function. The wordcloud module  then generated the image from the dictionary.
******************************************************************************************************
## Project goal 
Create a dictionary with words and word frequencies that can be passed to the generate_from_frequencies function of the WordCloud class.

Once you have the dictionary, use this code to generate the word cloud image:
1.cloud = wordcloud.WordCloud()
2.cloud.generate_from_frequencies(frequencies)
3.cloud.to_file("myfile.jpg")

## Things to remember 
1.Before processing any text, you need to remove all the punctuation marks. To do this, you can go through each line of text, character-by-character, using the isalpha() method. This will check whether or not the character is a letter.

2.To split a line of text into words, you can use the split() method.

3.Before storing words in the frequency dictionary, check if they’re part of the "uninteresting" set of words (for example: "a", "the", "to", "if"). Make this set a parameter to your function so that you can change it if necessary.

## Input file
For the input file, you need to provide a file that contains text only. For the text itself, you can copy and paste the contents of a website you like. Or you can use a site like Project Gutenberg to find books that are available online. You could see what word clouds you can get from famous books, like a Shakespeare play or a novel by Jane Austen.


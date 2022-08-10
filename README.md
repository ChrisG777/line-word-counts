# line-word-counts

## Steps to install
1. Make a copy of the template at https://docs.google.com/document/d/1qdmMyynQVeRRH2ugyzzzDNng3QcfnHmEB2B2iWUGIY4/edit?usp=sharing
2. On the top left of the doc, click Tools -> Script Editor
3. Press Run. If this is your first time, you’ll be prompted to give authorization to the script. Continue to your current google account, go to the bottom left where it says advanced settings, then the bottom left again, and give the script access.
4. Every time you want to refresh the word count, press Run again. 
5. On the google doc, where you adjust line spacing, turn off the option “Prevent single lines.” This is the equivalent of turning off widow and orphan control in microsoft word.


## Usage Tips

1. If you’re copy pasting in, make sure you’re using Times New Roman 12pt font
2. Don’t use very special characters: in particular, Chinese characters will not work. Numbers, dashes, punctuation marks, whatever are fine. Anything on your keyboard is fine. If you have to use a keyboard shortcut or copy paste the character from somewhere, it is probably not fine. 
3. Google docs counts em dashes (—) as a word. I count it as 0 words. Google docs word count counts 10,000 as two words. I count it as 1 word. A similar situation occurs for many symbols in the middle of a word (e.g. colons, slashes, periods)
4. For a regular essay, it will do completely cumulative word count. For a numbered list, it will reset the word count at each new number.

## Common Bugs
1. Q: The execution log is giving me “TypeError: Cannot read property ‘getCell’ of undefined”

  A: Check to see if you accidentally deleted the table. If you did, just make a new copy

2. Q: The word counts are right but they’re not aligned with my text

  A: Make sure that your text is single spaced and Times New Roman 12 pt font.

3. Q: There’s a large random jump in the word count

  A: Check to see if you used any characters that are nonstandard, like —>. If you did, delete those and figure out how to rephrase without using them. 

4. Q: The word counts are ending early

  A: Make sure that your indentation is correct. I assume that paragraphs are indented 0.5 inches at their start and nowhere else. Click on the front of your paragraph and look at the top of the page right below the font size. You should see a downward triangle and a rectangle. Move the triangle to 0 and the rectangle to 0.5 to indent properly.



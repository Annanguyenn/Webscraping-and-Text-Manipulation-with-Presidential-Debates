# Webscraping and Text Manipulation: Presidential Debates

Using Webscraping and Text Manipulation to perform analysis on Presidential Debates for the years from 1960 to 2012.

Tools: Python, Webscrapping with BeautifulSoup.


## Data

Scrape Presidential Debates from the Commission of Presidential Debates website: http://www.debates.org/index.php?page=debate-transcripts.

## Summary

1. By using `requests` and `BeautifulSoup` , I found all the links / URLs on the website that links to transcriptions of **First Presidential Debates** from the years [2012, 2008, 2004, 2000, 1996, 1988, 1984, 1976, 1960]. 

2. Analyze the data by reporting:
    1. Length of the transcript of the debate (as in the number of characters in transcription string).
    2. Count how many times the word **war** was used in the different debates.
    3. Scrape the most common used word in the debate, and how many times it was used.

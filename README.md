# Youtube_Comment_Analysis
# Objective: To find top 10 best similar comments to video transcript
# Description:
Semantic similarity is a confidence score that reflects the semantic relation between the meanings of two sentences. In this project I found semantic similarity between YouTube video transcript and its comments. Further I showed the best similar comments to transcript.

# Approach:
    
    First each sentence is partitioned into a list of tokens.
    
    Part-of-speech disambiguation (or tagging)
          
    Stemming words
          
    Find the most appropriate sense for every word in a sentence (Word Sense Disambiguation)
          
    Finally, compute the similarity of the sentences based on the similarity of the pairs of words.


# Steps:
 Extracted Youtube video subtitles/transcript using Youtube_dl
 
 Processed uncleaned downloaded transcript file using Transcript_read.py and saved it into required csv format(transcript.csv).
 
 Youtube comments are scraped using youtubeScrape.py and saved into csv/tsv file(test.csv and test.tsv).
 
 Performed comment analysis using NLP(nltk,wordnet,word_tokenize, pos_tag etc) as mentioned above.
 
 
# Open Youtube_comment_Analysis.ipynb

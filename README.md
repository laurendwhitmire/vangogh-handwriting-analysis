# vangogh-handwriting-analysis

This project aims to find a link between changes in someone's handwriting and the mood of what they are writing about. In other words, do changes in someone's handwriting indicate a change in their mood? To do this, I analyzed the letters of Vincent van Gogh. 

Overall project workflow:
- Download scanned images of van Gogh's letters. Scrape the transcripts for each.
- Use NLP to determine the sentiment of the transcribed text of each letter.
- Use a convolutional auto encoder to extract the physical features from the pages of letters. Use clustering analysis to group documents according to those physical features.
- Analyze the clusters of documents to see if there is any difference in sentiment that is tied to a physical difference in the letters.

# Chat Sentiment Analysis

A Python project analyzing an exported WhatsApp group chat: overall messaging statistics plus sentiment classification of the conversation.

## Notebooks

### Whatsapp Group Chat Analysis1.ipynb

General chat statistics - parses a raw WhatsApp chat export into a structured dataset and analyzes:

- Total messages, media, and links shared
- Most active member of the group
- Most active day of the week
- Per-author message breakdown

### WhatsApp Chat Sentiment Analysis.ipynb

Sentiment analysis on the same chat data - classifies messages as Positive, Negative, or Neutral, with polarity scoring, emoji handling, and a word cloud of frequently used terms.

## Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- TextBlob (sentiment/polarity)
- WordCloud

## Note

The original raw chat export used for this analysis has been removed from this repository (and its git history) since it contained real, private conversations - it is not included here.

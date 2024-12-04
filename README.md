# Swiftie Lyric Chatbot & Song Recommendation System

## Overview

This project provides an advanced chatbot for personalized song recommendations based on Taylor Swift's lyrics. It uses Natural Language Processing (NLP) techniques such as TF-IDF for lyric similarity analysis, sentiment analysis, and entity recognition to recommend songs based on user input. Users can customize their recommendations by applying filters such as album, sentiment, and theme keywords.

## Features

- **Song Recommendations**: Get personalized song recommendations based on lyric similarity.
- **Advanced Filters**: Apply filters for album, sentiment (positive, negative, neutral), and theme keywords to refine the recommendations.
- **Sentiment Analysis**: Analyze the sentiment (positive, negative, neutral) of songs in Taylor Swift's discography.
- **Entity Co-occurrence Graph**: Visualize the co-occurrence of named entities (e.g., characters, places) within album lyrics.
- **Entity Distribution Visualization**: Explore the distribution of entity types (e.g., people, places, events) across albums.
- **Chatbot Interface**: Interactive command-line interface that allows users to request song recommendations and apply various filters.

## Installation
1. Clone the GitHub repository containing Taylor Swift's lyrics: git clone https://github.com/ishijo/Taylor-Swift-Lyrics.git
2. The code will download the lyrics data for the original 10 albums defined in the original_10_albums list, specifically targeting the "Albums" folder.
3. The files will be copied into a local directory (./downloaded_files), maintaining the folder structure.

The code performs the following steps:
- Clones the repository.
- Checks for the existence of the relevant album folders.
- Copies the files from the GitHub repository to the local directory.
- Catches and displays any errors, and cleans up temporary files at the end.

## Usage 
Running the Chatbot
To start the chatbot and interact with the system, run the following command: chatbot_advanced()

The chatbot will ask for song inputs, and you can request song recommendations by typing the name of a Taylor Swift song. The chatbot will offer recommendations based on similarity and allow you to apply filters such as:
- Album Filter: Narrow recommendations to a specific album.
- Sentiment Filter: Filter by sentiment (positive, negative, neutral).
- Theme Keywords: Filter recommendations based on specific themes or keywords in the lyrics.

### Example
🎤 Welcome to the Advanced Swiftie Lyric Bot! 🎶
Looking for personalized song recommendations? Let's get started!
✨ Type the name of a Taylor Swift song, and I'll recommend others.
🎧 Add filters like album, sentiment, or themes for a tailored experience.
Type 'exit' anytime to leave. 💃

🎵 Your song choice (or type 'exit'): Love Story

🎶 Found your song: Love Story

📋 Do you want a single song recommendation or a playlist? (Type 'single' or 'playlist'): playlist

🎤 Want to filter by album? Type the album name or press Enter to skip: Fearless

🎭 Sentiment preference (positive/negative/neutral)? Press Enter to skip: positive

🌟 Key themes or keywords to match? Separate by commas or press Enter to skip: love, fairytale

🎶 Here are your top recommendations for 'Love Story':

1. You Belong With Me (Similarity: 0.89)
   
2. Enchanted (Similarity: 0.85)
...


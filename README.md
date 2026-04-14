# Song-analyzer
This program uses Gemini 2.5 flash to analyze song to help reduce the work of music critics and understand the song in various ways
# Song Analyzer

A Python-based tool that bridges the gap between popular music and academic literary analysis. This program automates the process of fetching song lyrics, cleaning the data, and using Generative AI to perform deep thematic and technical breakdowns.

## Overview
This project is designed for researchers, music critics, and students of literature who want to analyze the complexity of modern lyrics. It uses the Genius API for data collection and Google's Gemini 2.5 Flash model for high-level semantic analysis.

## Features
- **Automated Fetching:** Seamless integration with the Genius database to retrieve lyrics by song and artist name.
- **Data Preprocessing:** Uses the `cleantext` library to remove noise, fix encoding issues, and prepare text for AI processing.
- **Multidimensional Analysis:**
    - **General Critique:** Deep-dive into overall meaning and core metaphors.
    - **Thematic Deep-Dive:** Analysis of specific figures of speech and poetic devices.
    - **Career Impact:** Contextualizes the song within the artist's discography.
    - **Technical Analysis:** Evaluates rhyme schemes, double-entendres, and wordplay.

## Technical Stack
- **Language:** Python 3.10+
- **APIs:** LyricsGenius, Google Generative AI (Gemini)
- **Key Libraries:** `cleantext`, `google-generativeai`, `lyricsgenius`

## Setup & Usage
1. **API Keys:** Obtain API keys from Genius and Google AI Studio.
2. **Environment Variables:** Set your keys as environment variables to ensure security:
   - `GENIUS_API_KEY`
   - `GEMINI_API_KEY`
3. **Execution:** Run the script and follow the menu-driven interface:
   ```bash
   python main.py

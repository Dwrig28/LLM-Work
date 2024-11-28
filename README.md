# LLM-Work
# LLM-Powered NFL Game Recap Generator

## Overview
This project is an exploration of the power of Large Language Models (LLMs) in transforming data into creative outputs. The focus is on generating **NFL game recaps** influenced by various **musical artists** or other creative styles. The system integrates web scraping, AI-driven text generation, and audio synthesis to create engaging and dynamic content.

## Key Features
- **Data Collection**: Scrapes NFL game recaps from online sources.
- **LLM Integration**: Transforms structured sports data into poetic or storytelling styles inspired by user-specified artists.
- **Audio Outputs**: Synthesizes generated text into audio for a complete multimedia experience.
- **Customizable Prompts**: Allows users to specify NFL week, team, and stylistic influences for the output.

## Project Motivation
The goal of this project is to demonstrate how LLMs can:
1. Integrate seamlessly with external data sources.
2. Adapt to creative tasks while preserving factual accuracy.
3. Transform traditional sports analysis into shareable, personalized content.

This project combines my passion for sports, AI, and storytelling into an innovative demonstration of LLM capabilities.

## Technologies Used
- **Python**: The core programming language for the project.
- **OpenAI GPT**: For text generation tailored to specific styles.
- **Web Scraping**: BeautifulSoup and Selenium for automated data collection.
- **Audio Synthesis**: Converts generated text into speech.
- **Gradio**: Builds an interactive web-based interface for users.

## How It Works
1. **Input Parameters**: The user specifies the NFL week, team, and desired creative style (e.g., artist).
2. **Data Retrieval**: Game recaps are scraped from a reliable sports source.
3. **LLM Generation**: The recap is processed and rewritten in the specified artistic style.
4. **Output**: The recap is presented as text and optionally as synthesized audio.
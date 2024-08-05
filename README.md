# Movie Recommendation System with Sentiment Analysis

## Overview

This project is a Movie Recommendation System that uses sentiment analysis to suggest movies based on the user's mood. The system processes movie data and utilizes natural language processing to analyze user input, suggesting appropriate films based on sentiment.

## Features

- **Data Processing**: Cleans and filters movie and song data.
- **Genre Filtering**: Categorizes movies into genres and filters out non-relevant genres.
- **Sentiment Analysis**: Analyzes user input to determine sentiment (Positive, Negative, or Neutral).
- **Movie Suggestions**: Recommends movies based on sentiment analysis results:
  - **Positive Sentiment**: Suggests Comedy or Animation movies.
  - **Negative Sentiment**: Suggests Horror movies.
  - **Neutral Sentiment**: Suggests Action or Biography movies.

## Prerequisites

- Python 3.x
- Pandas
- NLTK (Natural Language Toolkit)

To install the required Python libraries, use the following commands:

```bash
pip install pandas
pip install nltk
```

## Setup

1. **Data Files**:
   - `movies.csv`: Contains movie information including genre and name.
   - `spotify_songs.csv`: Contains song data, although it's not utilized in the sentiment analysis process.

2. **Sentiment Analysis**:
   - Utilizes NLTK's SentimentIntensityAnalyzer to determine the sentiment of user input.

3. **Code Execution**:
   - The script processes movie data, performs sentiment analysis, and suggests a movie based on the sentiment detected from user input.

## How to Use

1. **Run the Script**:
   - Execute the script to start the recommendation process.
   
2. **Provide User Input**:
   - Enter a description of your day when prompted. The script will analyze the input to determine the sentiment.

3. **Receive Recommendations**:
   - Based on the sentiment analysis, the script will suggest a movie from the appropriate genre.

## Example

```plaintext
How was your day? Tell me about it: I had a great day!
```

```plaintext
I think you are in Positive mood
I suggest you to see [Suggested Movie Name] Released in [Release Year]
```

## Contributing

Contributions are welcome! To contribute, please fork the repository and submit a pull request. For major changes, please discuss them via an issue first.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- **NLTK**: For providing tools for sentiment analysis.
- **Pandas**: For data manipulation and analysis.

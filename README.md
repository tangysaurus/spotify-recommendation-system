# Spotify Recommendation System

### Description
This project uses content-based filtering and sentiment analysis to recommends songs to Spotify users based on listening history. It makes recommendations by comparing audio features retrieved from Spotify API and moods between different songs.

### Table of Contents
1. [Features](#features)
2. [Requirements](#requirements)
3. [Usage](#usage)
4. [License](#license)
5. [Data Sources](#data-sources)

### Features
- Get user authorization and access code, and exchange code for access token.
- Make requests to Spoitfy API for user listening history and audio features from song.
- Scrape song lyrics from Genius.
- Use cosine similarity to make recommendations.

### Requirements
This project requires the following Python libraries:
- pandas
- requests
- spacy
- BeautifulSoup
- scikit-learn
- NRCLex
  
### Usage
1. **Open the notebook**:
   - Download or open the Jupyter notebook from this repository.

2. **Run the notebook**:
   - Execute each cell in the notebook by running the provided Python code.

3. **Install dependencies** (if needed):

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Data Sources

Song features are retrieved from Spotify API [Spotify Web API](https://developer.spotify.com/documentation/web-api).
Song lyrics are retrieved from Genius [Genius](https://genius.com/)
Please refer to the individual sources for licensing details, terms of use, and citation requirements.

# Movie Recommendation App

This Movie Recommendation App is a web-based platform that uses embeddings and vector databases to generate personalized movie recommendations. The system processes movie metadata and user inputs to provide accurate and context-aware suggestions, enhancing their movie-watching experience.

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies Used](#technologies-used)


## Features
- Integrates with OpenAI’s text-embedding-3-small model for semantic understanding.
- Stores and queries data efficiently using the MyScale vector database.
- Enhanced recommendations through exponential decay for relevance scoring.
- Responsive web design for a seamless user experience.

## Recommendation Techniques

The app incorporates multiple approaches for content recommendation:  
1. **Content-Based Filtering**: Recommends movies based on attributes like genres, cast, and crew.  
2. **Collaborative Filtering**: Leverages user preference patterns to suggest movies enjoyed by similar users.  
3. **Hybrid Approach**: Combines content-based and collaborative methods for comprehensive recommendations.  
4. **Embedding-Based Search**: Uses vector embeddings to identify semantic similarities between movies and user inputs, enabling recommendations for nuanced content relationships.


## Demo
[Link to live demo](#) - (To be updated)

### Usage
Enter 3 movies.
The recommended movies will be displayed on the page.
Enter 0 to exit.

### Technologies Used
- OpenAI Embeddings
- Myscale vector database

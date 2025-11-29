# Movie Recommendation System (TMDB Dataset)

This project builds a content-based movie recommendation system using:
- Text preprocessing (genres, keywords, overview, cast)
- NLP vectorization (CountVectorizer / TF-IDF)
- Dimensionality reduction (Truncated SVD)
- KNN similarity search

The notebook walks through:
1. Loading and merging TMDB datasets  
2. Creating a cleaned `tags` feature  
3. Vectorizing text data  
4. Reducing dimensionality  
5. Fitting a KNN model  
6. Generating movie recommendations  

## How to run
Install dependencies:

```bash
pip install -r requirements.txt


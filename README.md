City Recommendation System for New Graduates.
Project Overview:
This project, part of the MSBA Fall 2024: Analytics for Unstructured Data course, aims to help new graduates find optimal cities to relocate based on their preferences. The system leverages scraped data from various city subreddits to recommend cities that match user-defined attributes.

Data was scraped from the top 20 U.S. city subreddits focusing on:
Post titles and bodies,
Upvotes,
Top comments,
Analysis, and 
Key Components

Word Counts: Analyzed based on total and weighted word counts per city.

Attributes: Important attributes identified include safety, housing, job availability, cost of living, and social venues.

Recommendation Model: Built using:
Attribute vector creation
City vectorization with Sentence Transformers
Similarity calculation using cosine similarity
Sentiment analysis integration for refining recommendations
Visualization
MDS Plot: Visualizing city similarities based on post content.

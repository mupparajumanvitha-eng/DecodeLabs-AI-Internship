# Smart Course Recommendation System

## Overview

The Smart Course Recommendation System is an AI-based content recommendation project developed using Python. This system recommends relevant courses based on a user's interests and preferred difficulty level. It utilizes TF-IDF Vectorization and Cosine Similarity to analyze user preferences and identify the most suitable courses from the available course database.

This project demonstrates the fundamental concepts of recommendation systems, which are widely used in platforms such as Netflix, Amazon, Spotify, and LinkedIn to provide personalized suggestions.

## Features

* Accepts user interests as input
* Filters courses based on difficulty level
* Uses TF-IDF Vectorization for text processing
* Calculates similarity using Cosine Similarity
* Recommends the Top 5 most relevant courses
* Displays match percentage for each recommendation
* Shows matched skills between user interests and course content
* Provides course duration and difficulty information

## Technologies Used

* Python
* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity

## Workflow

User Interests → Difficulty Filtering → TF-IDF Vectorization → Cosine Similarity Calculation → Ranking → Course Recommendations

## Sample Input

```
Enter your interests: python, ai, machine learning
Preferred difficulty: Intermediate
```

## Sample Output

```
SMART COURSE RECOMMENDATIONS

1. Machine Learning Fundamentals
   Match Score : 94%
   Difficulty  : Intermediate
   Duration    : 8 Weeks
   Matched Skills : ai, machine learning

2. Data Science with Python
   Match Score : 82%
   Difficulty  : Intermediate
   Duration    : 8 Weeks
   Matched Skills : python
```

## Learning Outcomes

* Recommendation Systems
* Content-Based Filtering
* Feature Extraction
* TF-IDF Vectorization
* Cosine Similarity
* AI Recommendation Logic
* Pattern Matching Techniques

## Future Enhancements

* Integration with CSV-based datasets
* User feedback and rating system
* Search history tracking
* Recommendation score visualization using charts
* Web application using Streamlit
* Personalized user profiles and recommendations

## Author

**Manvitha Chowdary Mupparaju**
Artificial Intelligence Intern, DecodeLabs

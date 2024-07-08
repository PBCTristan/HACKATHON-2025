# Project Architecture

```
HACKATHON-2025  
├── datasets  
│   ├── filtered_data  
│   │   ├── actors_actresses.csv  
│   │   ├── filtered_crew.csv  
│   │   ├── filtered_movies.csv  
│   │   ├── filtered_name_basics.csv  
│   │   ├── filtered_principals.csv  
│   │   └── filtered_ratings.csv  
│   └── raw_data  
│       ├── .gitignore  
│       ├── imdb_small.csv                  # Ignored, top 1000 IMDb dataset: [Link](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows)  
│       └── (.*).tsv                        # Ignored, original IMDb dataset: [Link](https://datasets.imdbws.com/)  
├── graphs  
│   └── graphs_genres_actors  
│       └── actors_(.*).graphml  
├── notebooks  
│   ├── ActorsDirectorsOccurences.ipynb     # Uses the smaller dataset to do Link Predictions
│   ├── CorrelationsAndDescriptors.ipynb    # Uses the full dataset to evaluates graph descriptors
│   ├── GraphClassification.ipynb           # Graph Classification on the full dataset
│   └── DatasetReduction.ipynb              # Needs to be executed first, creates filtered_data file
├── .gitignore  
└── README.md
```

# Description

This repository was used in Epita 2025 SCIA-G Hackathon.  
To execute notebooks/DatasetReduction, the original dataset linked above must be downloaded and put in the raw_data folder.
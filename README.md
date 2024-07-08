# Project Architecture

HACKATHON-2025  
├── datasets  
|   ├── .gitignore  
│   ├── filtered_data  
│   │   ├── actors_actresses.csv  
│   │   ├── filtered_crew.csv  
│   │   ├── filtered_movies.csv  
│   │   ├── filtered_name_basics.csv  
│   │   ├── filtered_principals.csv  
│   │   └── filtered_ratings.csv  
│   └── raw_data  
│       ├── imdb_small.csv.csv          # Ignored, top 1000 IMDb dataset: [Link](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows)
│       └── (.*).csv                    # Ignored, original IMDb dataset: [Link](https://datasets.imdbws.com/)
├── graphs  
│   └── graphs_genres_actors  
|       └── actors_(.*).graphml
├── notebooks
│   ├── ActorsDirectorsOccurences.ipynb
│   ├── debutdutruc.ipynb
│   └── reduction-dataset.ipynb
├── .gitignore 
└── README.md  
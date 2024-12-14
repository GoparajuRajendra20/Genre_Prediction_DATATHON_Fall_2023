# Music Genre Classification - Data Science Hub Datathon Fall 2023

## Overview
This project focuses on developing a machine learning model to predict music genres based on audio features and metadata. The model was developed as part of the Data Science Hub Datathon at Northeastern University, in collaboration with the Institute of Experiential AI.

## Competition Performance
- **Final Rank**: 15th place (Score: 0.60029)
- **Total Teams**: 36
- **Total Participants**: 70
- **Participation Type**: Individual
- **Achievement**: Secured a position in the top 40% as a solo participant

## Dataset Description

The dataset comprises multiple CSV files containing rich musical information:

### Main Files
- `train.csv`: Training dataset with song features and genre labels
- `test.csv`: Test dataset for predictions (public & private)
- `sample_submission.csv`: Template for submission format
- `meta_data1.csv` & `meta_data2.csv`: Supplementary feature information

### Key Features
- Basic song information (ID, album, artist, lyrics, track name)
- Audio characteristics (danceability, energy, instrumentalness, loudness)
- Technical metrics (duration, tempo, time signature)
- Additional metadata (release date, explicit content flag)

## Implementation Approach

### Data Preprocessing
- Handled missing values
- Encoded categorical variables (song_id, album, artist, lyrics, track)
- Standardized numerical features
- Feature selection and engineering

### Feature Engineering
- Combined audio features with metadata
- Created encoded versions of categorical variables
- Processed text data from lyrics

### Model Development
- Implemented Random Forest Classifier
- Used hyperparameter tuning with random_state=42
- Focused on audio features and metadata for prediction
- Key features used:
  - Audio characteristics (danceability, energy, loudness)
  - Metadata (release_date, explicit)
  - Encoded categorical variables

## Evaluation
- Model was evaluated on both public and private test datasets
- Final score achieved: 0.60029
- Ranked 15th among 36 competing teams

# DSAI3202 - Lab 3: Data Preprocessing on Azure

## Where you loaded from
Loaded the **Silver-layer curated_reviews Delta table** from:
`abfss://lakehouse@goodreadsreviews60XXXXXX.dfs.core.windows.net/processed/curated_reviews/`

## What cleaning was done
- Removed nulls and duplicates  
- Normalized and trimmed text  
- Dropped invalid or short reviews  
- Ensured correct data types (numeric rating, string IDs, valid dates)  
- Replaced missing values with safe defaults

## Features created
- `review_length` — number of words in each review  
- `avg_rating_book` — average rating per book  
- `num_reviews_book` — number of reviews per book  
- `avg_rating_author` — average rating per author

## Output
Saved the cleaned and feature-enriched dataset as **Delta** in:
`/gold/features_v1`

## Repository Structure


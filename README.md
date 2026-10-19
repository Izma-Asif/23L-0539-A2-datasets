# 23L-0539-A2-datasets
# Assignment 2 Cleaned Datasets (v1.0)

**Date:** 19 October 2026 | **Version:** v1.0

## Netflix (23L_0539_A2_netflix_cleaned.csv)
- **Source:** Kaggle, "Netflix Movies and TV Shows" by shivamb (https://www.kaggle.com/datasets/shivamb/netflix-shows). All rights belong to the original author and the dataset follows its licence.
- **Changes:** trimmed whitespace; moved "min" values wrongly stored in `rating` into `duration`; converted `date_added` to a date; filled missing director, cast, country and rating with "Unknown"; added year_added, month_added, release_to_added_gap, num_countries, num_genres, num_cast, duration_min, num_seasons, rating_group and release_decade. No outliers were removed.

## Supermarket Sales (23L_0539_A2_supermarket_cleaned.csv)
- **Source:** supermarket_Sales.csv, provided by the instructor (FAST-NU, Lahore).
- **Changes:** converted Date and Time to proper formats; added month, weekday, is_weekend, hour and day_part. No rows were removed (no missing values or duplicates found).
